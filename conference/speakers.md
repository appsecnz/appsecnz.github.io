---
layout: conference-2022/full-width
title: Speakers and Abstracts
description: Presentation Abstracts and Speaker Biographies - OWASP NZ Day 2022
---

[![Web Banner](/assets/images/2022_Banner_Graphic.jpg)](/conference/)   
[Back to Conference Home Page](index.md)
{: style="text-align: right; font-size: small;" }

# Presentation Abstracts and Speaker Biographies

## OWASP New Zealand Day 2022

Presentations are listed on this page in alphabetical order by title.

-----------

### Application Security and Cheese   
*Steve Esler - Aura Information Security*   
Track One   
Thursday, 15:05


#### Abstract

Everyone loves cheese, right? This talk will apply the Swiss cheese model to AppSec, each cheese slice is a security activity, a layer of the defenses there to reduce the risk of threats becoming reality and prevent vulnerabilities from various sources making their way into production systems.
 
#### Description

This talk leans on some of my background in aviation maintenance and safety software as aviation is one of the places where the Swiss cheese model originated. It has also been used more recently to model the COVID pandemic defenses. I will apply the model here to describe how we can use security activities in the application development lifecycle to reduce the risk of threats becoming a reality. Each slice of the cheese being a security activity, each hole being a gap in the defenses that a threat might slip through. It will describe what in application security context active and latent failures are and in this context how vulnerabilities can relate to the four failure domains of the model: organizational influences (poor security culture, priorities elsewhere, lack of investment), supervision (training and guidance, documentation), preconditions (lack of controls, complex environments) and specific acts (activities of the threat actor, poor security practices).

No new ground-breaking security activities here; just all the good stuff championed by OWASP and explaining how these can fit into common software development lifecycles. Covering about how threats might still slip through, what might move the slices making the holes align or new ones appear so a threat could get through and become a vulnerability by looking at some of the limitations of each activity. What could be the next slice of cheese that might catch the threat and avoid an incident later in the development lifecycle. Share some of my experience in understanding when to do each activity and the problems I've previously encountered in working with development teams to introduce application security programs. Telling a story of some of the things I have seen work in practice, some that haven't worked so well and questions that often come up when planning and implementing a set of security activities. It's not a one size fits all, some activities will suit individual contexts better than others. How layering is key both to provide defense in depth but also to enable a gradual rollout as the activities cost both effort and money. Delving briefly into what can be automated and what is best accepted as a manual process. Also looking at some of the Human Factors that influence the effectiveness of the defenses.

#### Speaker Biography

**Steve Esler** has a background in 15 years as a web developer working on greenfield projects and initiating changes in development technologies prototyping new systems that I then helped release to market. The last 5 years as a developer I spent working with the Royal Air Force in the UK on an aircraft maintenance and support software. After meeting all the goals I’d set myself for a development career I switched to Cyber Security to take on a new challenge. And there are possibly no wider fields and challenges than Cyber Security! Gained a Masters in Cyber security then went out to industry to gain some experience starting with a short stint as a pen tester then moving on to working securing on IoT, SCADA electronics systems and vulnerability management for a custom Linux distro at Honeywell. At Honeywell, I was working with teams across the world to secure both hardware, operating systems and applications. Through Honeywell, I picked up some great experience working within a very mature and successful software and system security program. Also gaining some professional certificates along the way. I then worked with a large financial company in the UK on creating an application security framework before moving to New Zealand with my young family at the start of 2021.

-----------

### Building Your First DevSecOps Pipeline   
*Karan Sharma - Wise Fox Security*   
Track Two - Thursday, 15:05   


#### Abstract

I am sure all of you have heard about "Shift Left Security" in many presentations, but how do you actually achieve this? Well, this is the talk for you where I'll cover all the DevSecOps buzzwords and showcase a functional DevSecOps pipeline that can perform security testing such as SCA, SAST and DAST.

#### Description

In this talk I'll cover how to build your first DevSecOps pipeline with Open Source tooling. I'll address various concepts and buzzwords related to DevSecOps to clear your doubts. I'll demonstrate a GitLab pipeline that has various open-source security tooling embedded to perform the following security tests against a vulnerable application:

* Secrets Detection (tools such as Trufflehog, etc.) 
* Software Composition Analysis (SCA)
* Static Application Security Testing (SAST)
* Dynamic Application Security Testing (DAST)

With this pipeline, our aim is to identify security issues as early as possible so that we can build "Secure by Default" products. This pipeline and demos will cover tools such as retireJS, Safety, Bandit, TruffleHog, NMAP, SSLyze and ZAP.

#### Speaker Biography

**Karan Sharma** has been in this field for over 11 years. He has worked as a Pentester for NZ telcos, banks, health sectors and manufacturing companies. He now runs his own security consulting company called Wise Fox Security, that offers services in Offensive Security and DevSecOps space. He has also done a few customary certifications such as OSWE, OSCP, eWPTX and Certified DevSecOps Professional (CDP). He has also spoken at a number of other security conferences. Karan has a YouTube channel that you can subscribe to (Wise Fox Security). Other than InfoSec, Karan loves watching and playing soccer, loves evening runs with his dog and going to the gym.

-----------

### A Deep Dive into Kubernetes Schema Validation   
*Eyar Zilberman - datree*   
Remote Presentation   
Track Two - Thursday, 13:30   


#### Abstract

How do you ensure the stability of your Kubernetes (K8s) clusters? Are you sure you don't have any invalid data types? Are any mandatory fields missing? Specialized tools and a "shift-left" approach make it possible to verify a Kubernetes schema before it's applied to a cluster.

#### Description

How do you ensure the stability of your Kubernetes clusters? How do you know that your manifests are syntactically valid? Are you sure you don't have any invalid data types? Are any mandatory fields missing? Most often, we only become aware of these misconfigurations at the worst time - when trying to deploy the new manifests.

In this talk, we will review how to overcome this challenge with OSS tooling that can be integrated seamlessly into your deployment process.

#### Speaker Biography

**Eyar Zilberman** started his professional life as a lawyer for OSS licenses, but fell in love with the technology itself. He taught himself to code and worked as a full-stack engineer. After about four years, he decided he needed to step out of his comfort zone, and today he's an entrepreneur and Chief Product Officer at [Datree](https://datree.io)

-----------

### Fantastic GraphQL Bugs and Where to Find Them   
*Hotanya Ragtah - CyberCX*   
Track Two - Thursday, 11:30   


#### Abstract



#### Description



#### Speaker Biography

**Hotanya Ragtah** 

-----------

### Fix Every Instance   
*Tim Goddard - CyberCX*   
Track One - Friday, 14:25   


#### Abstract



#### Description



#### Speaker Biography

**Tim Goddard** 

-----------

### Forging a Response to Log4Shell using OWASP ModSecurity Core Rule Set (CRS)   
*Kirk Jackson - RedShield*   
Track Two - Thursday, 15:05   


#### Abstract



#### Description



#### Speaker Biography

**Kirk Jackson** 

-----------

### Let's Pick Our AppSec Toolkit   
*Raafey Khan - Datacom*   
Track One - Thursday, 15:30   


#### Abstract



#### Description



#### Speaker Biography

**Raafey Khan** 

-----------

### Mapping Your External Perimeter during an Incident with OWASP Amass   
*Kento Stewart - Westpac*   
Track Two - Thursday, 10:55   


#### Abstract



#### Description



#### Speaker Biography

**Karan Sharma** 

-----------

### Minimum Viable Security for Microservices   
*David Melamed - Jit*   
Remote Presentation   
Track Two - Thursday, 10:20   


#### Abstract



#### Description



#### Speaker Biography

**David Melamed** 

-----------

### Mobile Wanderlust! Our journey to version 2.0   
*Sven Schleier - OWASP MSTG and MASVS Projects*   
Track One - Friday, 11:30   

#### Description

There are numerous ways of developing mobile applications today, but how do you ensure that security is part of the development process? What are the attacks you should be concerned about and what can you do to avoid being an easy target? If you don't want to miss anything, leveraging a standard is essential. 

The Mobile Application Security Verification Standard (MASVS) offers exactly that. It works together with the agile-written Mobile Security Testing Guide (MSTG) to help you understand the attack surface of mobile apps, how to exploit them and how to protect them. Both resources are crafted and curated by a team of industry experts and community contributors.

In this talk we will make a deep dive into the upcoming changes of both projects and the transition to version 2.0. We are sharing the current status of the refactoring of the OWASP MASVS and the MSTG and what we've been able to automate to get rid of manual processes and have more time focusing on the content!

#### Speaker Biography

**Sven Schleier** is the Technical Director of F-Secure Singapore and has hands-on experience in attacking and defending web and mobile apps for the last 10+ years. He became specialised in Application Security and has supported and guided software development projects for Mobile and Web Applications during the whole SDLC.

Besides his day job, since 2016, Sven has been one of the core project leaders and authors of the OWASP Mobile Security Testing Guide (MSTG) and OWASP Mobile Application Security Verification Standard (MASVS) and has created the OWASP Mobile Hacking Playground. Sven gives talks and workshops about Mobile Security worldwide to different audiences, ranging from developers to students and penetration testers.

-----------

### Not under the Doormat: Securing your database credentials on the web application client-side   
*Helen Huang - Aura Information Security*   
Track Two - Friday, 10:55   


#### Abstract



#### Description



#### Speaker Biography

**Helen Huang** 

-----------

### The OWASP Internet of Things (IoT) Top 10   
*Tom Isaacson*   
Track One - Thursday, 13:30   


#### Abstract



#### Description



#### Speaker Biography

**Tom Isaacson** 

-----------

### OWASP Top 10 Overview   
*Kirk Jackson - RedShield*   
Track One - Thursday, 10:20   


#### Abstract



#### Description



#### Speaker Biography

**Kirk Jackson** 

-----------

### Pentesting at Scale   
*Caroline Wong - Cobalt Labs*   
Remote Presentation   
Track One - Friday, 15:30   


#### Abstract



#### Description



#### Speaker Biography

**Caroline Wong** 

-----------

### PIACERE: DevSecOps Automated   
*Rados&#322;aw (Radek) Piliszek - 7bulls*   
Track Two - Friday, 10:20   


#### Abstract



#### Description



#### Speaker Biography

**Rados&#322;aw Piliszek** 

-----------

### Server-Side Request Forgery (SSRF): The community push to the OWASP Top 10   
*Nick Lauder - Quantum Security*   
Track Two - Thursday, 14:25   


#### Abstract



#### Description



#### Speaker Biography

**Nick Lauder** 

-----------

### State of AppSec in New Zealand - 2022   
*John DiLeo - Datacom*   
Track One - Friday, 10:20   


#### Abstract



#### Description



#### Speaker Biography

**John DiLeo** 

-----------

### Ten Free Uplifts for Protecting Small Businesses   
*Sam Shute - Quantum Security*   
Remote Presentation   
Track One - Friday, 10:55   


#### Abstract



#### Description



#### Speaker Biography

**Sam Shute** 

-----------

### The Three Disciplines of CI/CD Security   
*Daniel Krivelevich - Cider Security*   
Remote Presentation   
Track One - Thursday, 14:25   


#### Abstract



#### Description



#### Speaker Biography

**Daniel Krivelevich** 

-----------

### Top 10 Security Risks in CI/CD Systems   
*Omer Gil - Cider Security*   
Remote Presentation   
Track Two - Thursday, 15:30   


#### Abstract



#### Description



#### Speaker Biography

**Omer Gil** 

-----------

### Validating Configs from Code to Deployment in the GitOps World   
*Noaa Barki - datree*   
*Shimon Tolts*   
Remote Presentation   
Track Two - Friday, 14:25   


#### Abstract



#### Description



#### Speaker Biographies

**Noaa Barki** 

**Shimon Tolts** - No biography provided

-----------

### Waiter, There's a CVE in My SOUP!   
*Kevin Alcock - Datacom*   
Track One - Thursday, 10:55   


#### Abstract



#### Description



#### Speaker Biography

**Kevin Alcock** 

-----------

### When Twiddling the Dials Goes Wrong   
*Shofe Miraz - Insomnia Security*   
Track Two - Friday, 11:30   


#### Abstract



#### Description



#### Speaker Biography

**Shofe Miraz** 

-----------

### Who Are You and Why Are You in My House?   
*Stephanie (Steph) Dean*   
Remote Presentation   
Track One - Friday, 13:30   


#### Abstract



#### Description



#### Speaker Biography

**Steph Dean** 

-----------

### Why Do We Really Need OAuth?   
*Aaron Parecki - Okta*   
Remote Presentation   
Track One - Thursday, 11:30   


#### Abstract



#### Description



#### Speaker Biography

**Aaron Parecki** 

-----------


