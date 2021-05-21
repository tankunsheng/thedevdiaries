---
title:  "CloudFormation !Ref. Not not Ref"
date:   2021-03-30 16:00:22 +0800
categories: CloudFormation, Tech
---

## !Ref is not, 'Not Ref'. Ref might not be what you want too

Nobody thinks it is 'Not Ref', but it certainly looks the part to anyone who has ever written any kind of code (most likely everyone in Tech). I have always thought the crew behind the inception of CloudFormation to be a bunch of hipsters. The syntax certainly look the part, it is... non-conventional. From the '!' messing with the minds of software developers to double colons '::' seldomly used and seen in modern, higher level languages, to **'Ref'** returning different values depending on which resource type you use it on.

### What is !
'!' is just the short-hand syntax for expressing intrinsic functions.

For example, you could write '!Sub', instead of 'Fn::Sub:' if wish to use the **'Sub'** intrinsic function,. 
However, this is awkward for the use case of Ref, also an intrinsic function, as you could write '!Ref' instead of 'Ref:- which is definitely more redundant and confusing than convenient. 
And why not remove the non short-hand syntax entirely, rather than having multiple ways to attain the same outcome. Newcomers are going to be confused when looking at different example templates, possibly written by many people, all using different ways to express the same things.

### Ref, no gimme what me want
Depending on your initial experience with using **'Ref'**, you might be lured into a preconceived notion of what it returns. I certainly did, at the start.

Turns out, **Ref returns different values depending on which Resource Type you are calling it on**. For example, Reffing an AWS::SNS::Topic returns the ARN of the topic while Reffing AWS::SQS::Queue returns the queue URL instead. You never know what you will be getting unless you check the docs, read the docs, breathe the docs.


## TLDR
I personally find CloudFormation to be slightly more unwieldy, with more pitfalls and gotchas to lookout for as compared to say, Terraform. Its relative unintuitiveness makes for a more difficult learning curve for people who are getting started on it. Its syntax expressions is certainly hard to deduce without checking the docs, even after looking through many example templates. The fact that the syntax can be expressed differently for the same outcomes, and the retrieval of different results for the same expression certainly makes it harder for new comers.

