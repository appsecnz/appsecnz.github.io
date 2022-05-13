---
title: Classroom Training - Automated Security Regression Testing with OWASP PurpleTeam
description: Pre-Conference Training Class, 6 July - OWASP New Zealand Day 2022 

layout: full-width
dataDir: conference-2022
sponsorsEventName: OWASP New Zealand Day 2022
---

[![Web Banner](/assets/images/2022_Banner_Graphic.jpg)](/conference/)   
[Back to Pre-Conference Training Page](training.md)
{: style="text-align: right; font-size: small;" }   
[Back to Conference Home Page](index.md)
{: style="text-align: right; font-size: small;" }   

# Automated Security Regression Testing for Web Apps and APIs with OWASP PurpleTeam

## CANCELLED One-Day Interactive (Classroom) Training - OWASP New Zealand Day 2022

## Abstract

Let's get your Web Apps and APIs under security regression testing with OWASP PurpleTeam. In this workshop, you will bring the Web app and/or API that you and/or your Development Team are working on and we will help you setup PurpleTeam locally on your laptop or infrastructure to test your App or API.

## Course Details 

**Dates:** Wednesday, 6 July 2022

**Time:** 8:45 a.m. to 5:30 p.m. (NZDT)

**Instructor:** Kim Carter, Leader, [OWASP PurpleTeam Project](https://owasp.org/www-project-purpleteam/)   

**Course Fee:** NZ $500.00 (plus GST and ticketing fees)

**Registration Site:** [https://events.humanitix.com/owaspnz2022-training](https://events.humanitix.com/owaspnz2022-training){: target="training-reg" }

**Maximum Enrolment:** 36 attendees

## Course Description

OWASP PurpleTeam is a Developer-focused security regression testing CLI (front end) and SaaS (back end) that targets Web 
Applications and APIs. Its sweet spot is sitting in build pipelines. The CLI and SaaS can be run from any Linux platform. 
PurpleTeam can be run in [UI mode with a pretty CUI or headless](https://github.com/purpleteam-labs/purpleteam#ui), informing 
the Build User in real time of the testing effort that is taking place in the back end as the 
[Tester Emissaries](https://purpleteam-labs.com/doc/definitions/) security test your system under test (SUT). 
UI mode is great for getting started so you can see what’s happening in real-time. Headless mode has been designed to be 
run from your CI, nightly build pipelines. The two modes are easily switchable.

In this workshop (time permitting) you will set up the [back-end components](https://purpleteam-labs.com/doc/local/set-up/#purpleteam-local-architecture), 
install and configure the [CLI](https://github.com/purpleteam-labs/purpleteam), create your *[Job](https://purpleteam-labs.com/doc/jobfile/)* file, 
which specifies how to find and test your target system under test (SUT).

No actual tests need to be written. PurpleTeam is smart enough to know how to test your Web Apps and APIs.

You can work alone or within a team (ideally with engineers from your daily workplace). In addition to the 
satisfaction of having your Web app or API being under security regression testing, there will also be prizes for 
each individual or team that gets OWASP PurpleTeam up and running testing their BYO SUT (Web app or API).

## What You Need Up Front

A decent night's sleep before. There is a lot to get done in this short period of time!

You will need either a Web Application or API, either reachable from the Internet or locally within a Docker container 
that you can put into a docker-compose file in the same Docker network as PurpleTeam local, or on the day you can spin 
up an instance of NodeGoat (or something else) as a local Docker container to join the local PurpleTeam docker network. 
If you decide to use NodeGoat, we will provide a docker-compose override file.

If you intend on targeting an application or API on the Internet, you will need to prove you own or are responsible for 
it -- this is non negotiable. You can do this by adding a DNS TXT record “PurpleTeam_SUT” or by adding the same text 
to the source of your app or API.

## Things you should try to do and/or have set up before the workshop

These items are just time consuming to set up and are not specifically PurpleTeam-related, so you really should try 
to have these set up before the workshop.

Work through the [local documentation](https://purpleteam-labs.com/doc/local/set-up/) and the README files of each project, 
so you are at least familiar with what the steps are going to be. The more you get done before the workshop, the more likely 
you will be to have PurpleTeam security regression testing your target Web app or API by the end of the workshop. 

You will need the following:

* A Linux laptop or Linux OS
* Docker and docker-compose installed
* Either a SUT (Web app or API) on the Internet to target, or a local Web app or API in a Docker container that can be
added to the PurpleTeam docker network (usually, via docker-compose file override)
* Git (you will be cloning or forking PurpleTeam repos)
* An AWS user with CLI access, policy, credentials configured, AWS CLI, aws-sam-cli installed and configured per the
instructions in the [purpleteam-lambda README](https://github.com/purpleteam-labs/purpleteam-lambda). We don't need to 
access AWS with the local environment, but you need to have the user set up as per the README.
* (Optional) Recommend having a copy of [OWASP ZAP](https://www.zaproxy.org/) GUI ready to run on your desktop. Using ZAP 
desktop to work through some of the steps that PurpleTeam does, just makes it easier to debug and understand what PurpleTeam is doing.

## Your Instructor

**Kim Carter**

Kim is the founder of BinaryMist Ltd and PurpleTeam-Labs. He is a published author of several information security books specifically targeting Software Engineers, DevOps Engineers, and Architects. He has hosted, and been a guest on, many podcasts involving information security, including being a host for Software Engineering Radio.

He has written over 100 Blog posts covering software engineering and information security topics. Kim has spoken at many international conferences and run many workshops helping Software Engineers understand and improve their information security.

Kim pioneered the InfoSecNZ Slack, served as the OWASP New Zealand Chapter Lead for Christchurch for eight years, and co-pioneered the Christchurch Hacker Conference (CHCon). Kim continues to consult with Software Engineering Teams on a daily basis to improve their security, quality and reduce their time to delivery.
