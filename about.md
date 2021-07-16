---
layout: page
title: About Me
permalink: /about/
---

I am a full-stack software engineer who is interested in bettering my understanding of the entire life cycle of software development, one day at a time.

My interest areas include
1. Web application development in both the frontend and backend, such as **React, Vue, NodeJs**. 
2. AWS Cloud Infra as code automation tools, such as **Serverless Framework, Terraform, CloudFormation, and Cloud Development Kit**.
3. CICD solutions such as **GitLabCI, GitHub Actions, Bamboo**.
4. Containerization and container platform orchestration technologies, such as **Docker and Kubernetes**.

I am also

_A gamer with a love for RPG games._

_A bathroom vocalist._

_A "woke" salary-man._

_A realist._
<br/><br/><br/>

<!-- Every software dude/gal out there has got ~~a story~~ **many stories**.
Here I am, sharing mine. Feel free to email <span class="text-accent">thedeveloperdiaries@gmail.com</span> if you have anything interesting to share! -->

---

# Work Experience

## Oct 2019 – Current

<div class="container table">
    <div class="prose col-6 sm-width-half left">
        <img src="/assets/img/govtech-logo.png"/>
    </div>
</div>
### GovTech Singapore
##### Software Engineer
Working on <a style="color:blue" target="_blank" href="https://www.developer.tech.gov.sg/">**Developer’s Portal**</a>, a centralized portal to facilitate discovery of government digital products and services.
*	Working on <a style="color:blue" target="_blank" href="https://docs.developer.gov.sg/">**Documentation Portal**</a>, a whole of government documentation service for publishing, searching, and reading software documentation.
  *	Contributed to refactoring and migration of frontend and backend from vanilla Javascript to Typescript. **Vue** and **ExpressJS**.
  *	Developed features such as the documentation publishing flow which allow users to authorize publication of docs from a Git repo of a Git Provider of their choice (GitHub, GitLab).

Worked on **APEX**, a whole of government API gateway for data sharing across government agencies
* Assumed responsibility over OpenAM, a single sign-on authorization server, and its integration with various client applications. Familiarity in OAuth2 and OIDC specs.
* Worked on APEX Cloud and Kubernetes redesign on AWS EKS.
  * Created CI pipelines for building docker images with Bamboo to Nexus.
  * Utilized GitOps to enable cluster management through git as the source of truth with FluxCD, Bitbucket and Nexus.
  * Extended Kubernetes Custom Resource Definitions and controller for managing custom app configurations.
  * Developed backend services in NodeJS (NestJS) to be deployed in Kubernetes cluster.
<br/><br/>

## Jun 2018 – Oct 2019

<div class="container  table">
    <div class="prose col-6 sm-width-half left">
        <img src="/assets/img/ura-logo.png"/>
    </div>
</div>
### Urban Redevelopment Authority (Digital Planning Lab)	
##### Systems Analyst
Worked on ePlanner, an inter-agency Web GIS platform with map layers powered by cross agency datasets to facilitate various planning decisions and more.
*	Gathered requirements in inter-agency discussions to understand cross domain knowledge and pain points so that a GIS solution can be designed.
*	Performed data exploration, preparation and construction of spatial SQL queries to unlock value in spatial datasets with **PostGIS**.
*	Developed map layers on **React** web app with LeafletJS, using map services served through Geoserver and Esri mapservers.
<br/><br/><br/>

---

# Education

## Aug 2014 – Jun 2018

<div class="container  table">
    <div class="prose col-6 sm-width-half left">
        <img src="/assets/img/smu-logo.png"/>
    </div>
</div>
### Singapore Management University 
##### BSc in Information Systems  
*	SMU Scholar, CGPA 3.65/4.0
*	Placed on Dean’s List in Academic Year 2016-2017
<br/><br/>

## Apr 2011 – Apr 2014

<div class="container table mt-2">
    <div class="prose col-6 sm-width-half left">
        <img src="/assets/img/nypsit-logo.png"/>
    </div>
</div>
### Nanyang Polytechnic
##### Diploma in Business Informatics 
*	Microsoft Bronze Medalist, CGPA 3.91/4.0
*	Placed on Director’s List for all semesters
<br/><br/><br/>

---
<h1 
  id="Projects"
  class="header-title sm-width-full py-3 mt-3">
  Projects
</h1>
<a href="https://play.google.com/store/apps/developer?id=Apps+Conversion+Express" target="_blank">Google Playstore Link</a>
 

{% for project in site.projects %}
{% include project_block.html %}
{% endfor %}

&nbsp;

------
<h1 
  id="Certs"
  class="header-title sm-width-full py-3 mt-3">
  Certifications
</h1>
<div class="container mx-auto px-2 table">
      
  {% for cert in site.certs %} {% include cert_block.html %} {%
  endfor %}
  </div>

---

# Quotes to live by

> "As long as the **spirit** endures, everything can be rebuilt"

> "We who cut mere stones must always envision cathedrals"

<!-- <h1>Skills</h1> -->
