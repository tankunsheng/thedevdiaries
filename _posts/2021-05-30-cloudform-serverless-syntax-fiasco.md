---
title:  "CloudFormation !Ref. Not not Ref"
date:   2021-03-30 16:00:22 +0800
categories: CloudFormation, Tech
---

## !Ref is not, 'Not Ref'. Ref might not be what you want too

Nobody thinks it is 'Not Ref', but it certainly looks the part to anyone who has ever written any kind of code (most likely everyone in Tech). I have always wondered if the designers of CloudFormation are a bunch of hipsters because the syntax they came up with for CloudFormation certainly reflects a sort of exuberance and flair. From '!' messing with the minds of software developers to the double colons '::' not commonly seen in modern languages, to Ref referencing different values for different resource types and the different ways to express the same functions.

### What is !
'!' is just a shortened syntax of its counter part, a different syntax to express the same thing. 

For the example of the Sub intrinsic function, you would write '!Sub', instead of 'Fn::Sub:'. 
It feels awkward in the use case for the intrinsic function of Ref as you would write '!Ref' instead of 'Ref:' - which is definitely more redundant and confusing than convenient. 
And why not remove the non-shorthand version entirely rather than having multiple ways to achieve the same outcome. New peep are going to be confused when looking at different examples using different ways to express the same things.

### Ref, no gimme what me want
Depending on your initial experience with using **'Ref'**, you might be lured into a preconceived notion of what it returns. I certainly did, at the start.

Turns out, **Ref returns different values depending on which Resource Type you are calling it on**. For example, Reffing an AWS::SNS::Topic returns the ARN of the topic while Reffing AWS::SQS::Queue returns the queue URL instead. You never know what you will be getting unless you check the docs, read the docs, breathe the docs.


## TLDR
I personally find CloudFormation to be slightly more unwieldy, with more pitfalls and gotchas to lookout for as compared to say, Terraform. Its relative unintuitiveness makes for a more difficult learning curve for people who are getting started on it. Its syntax expressions is certainly hard to deduce without checking the docs, even after looking through many example templates. The fact that the syntax can be expressed differently for the same outcomes, and the retrieval of different results for the same expression certainly makes it harder for new comers.

