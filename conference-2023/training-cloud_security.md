---
title: Classroom Training - Cloud Security Masterclass
description: Pre-Conference Training Class, 4-5 July - OWASP New Zealand Day 2023 

layout: conference/full-width
dataDir: conference-2023
sponsorsEventName: OWASP New Zealand Day 2023
---

[![Web Banner](/assets/images/2023_Banner_Graphic.jpg)](/conference/)   
[Back to Pre-Conference Training Page](training.md)
{: style="text-align: right; font-size: small;" }   
[Back to Conference Home Page](index.md)
{: style="text-align: right; font-size: small;" }   

# Cloud Security Masterclass: Defender's guide to securing AWS and Azure infrastructure

## Two-Day Interactive (Classroom) Training - OWASP New Zealand Day 2023

## Abstract

Enhance your cloud security knowledge to defend AWS and Azure infrastructure and apps through building automated detection, alerting, and response systems. This training offers hands-on labs, CTF Challenges (metal coins to win), and attack simulations for a practical learning experience.

#### Key Takeaways

* Using cloud native technologies to build your own security services for your applications and services running in the cloud
* Building real-time detection, monitoring and response capabilities for threat tracking and intelligence gathering
* Building Advanced automated pipelines through Detection-as-code features to defend public cloud infrastructures

## Course Details 

**Dates:** Tuesday and Wednesday, 4-5 July 2022

**Time:** 8:45 a.m. to 5:30 p.m. (NZST)

**Instructor:** Abhinav Singh   

**Course Fee:** NZ $1,000.00 (plus GST and ticketing fees)

**Registration Site:** [https://events.humanitix.com/owaspnz2023-training](https://events.humanitix.com/owaspnz2023-training){: target="training-reg" }

**Maximum Enrolment:** 36 attendees

## Prerequisites - What Students Should Bring

* Basic understanding of cloud services
* System administration and Linux CLI
* Able to write basic programs in Python
* Familiarity with SQL and KQL queries will be a plus

### Hardware and Software: Attendees should bring:

* A laptop with Internet access
* AWS Free Tier account, with command-line tools installed
* Azure Free Tier account, with command-line tools installed
* Read and complete the pre-training briefing document that will be sent a week before the training date

## What Students Will Be Provided

* PDF versions of slides that will be used during the training
* Complete course guide PDF, containing over 200 pages - It will contain step-by-step guidelines for all the exercises, labs, and a detailed explanation of concepts discussed during the training
* Over 20 pages of cloud security rulebook, to implement cloud security controls in an enterprise
* 15 days' access to Slack channel and CTF platform
* Infrastructure-as-code templates, for deploying the test environments and simulations, for continued practice after the class ends
* Access to Github account for accessing custom-built source codes and tools
* Collection of test malware samples, forensic images, detection rules and queries

## Why Should You Attend?

This is a unique course that is on the cloud and for the cloud. It helps train individuals on cloud terminologies and enables them to build scalable defense mechanisms for their services running in the public cloud. The training explicitly focuses on threat detection, Incident response, malware investigations, and forensic analysis of cloud infrastructure which is still a very less known domain in the market. The training is not going to use cloud-native security tools, but going to focus more on building analysis pipelines that are generic and can be implemented in any cloud environment.

## Course Description

This training takes both investigator and builder approach towards security. It teaches you the fundamentals of cloud infrastructure security and focuses on building highly scalable threat detection, monitoring, and response tools by using cloud-native services like serverless, containers, object stores, IAM/AD, logic apps, SQL/KQL queries and much more.

By the end of this training, we will be able to (applies to both AWS & Azure): 

* Use cloud technologies to detect and build automated responses against IAM and AD attacks
* Understand and mitigate advanced identity-based attacks, like pivoting and privilege escalation, and build defense techniques against them
* Use serverless functions to perform on-demand threat scans
* Deploy containers to build threat detection services at scale
* Build notification services to create detection alerts
* Analyze malware-infected virtual machines to perform automated forensic investigations
* Define step functions and logic apps to implement automated forensic artifacts collection for cloud resources
* Build cloud security response playbooks for defense evasion, persistence and lateral movements
* Perform advanced security investigations through architecting and deploying security data-lake for real-time threat intelligence and monitoring
* Enforce multi-cloud security strategy through assessments, compliance checks and benchmarking automation

## Course Outline 

### Day 1

#### Introduction

* Quick Introduction to AWS & Azure cloud services
* Basic terminologies: IAM, VPC, AMI, serverless, ARNs, etc.
* Introduction to Logging services in cloud
* Setting up your free tier account 
* Setting up AWS and Azure command-line interface

#### Cloud Attack Surface

* Cloud service enumeration for attack surface identification  
* Exploiting serverless functions and harvesting cloud credentials

#### Detecting and Monitoring against AWS IAM Attacks

* Identity and Access management (IAM) crash course
* Policy enumeration from an attacker's and defender's perspective
* Detecting and responding to user account brute-force attempts
* Building controls against privilege escalation and access permission flaws
* Attacking and defending against user role enumeration
* Brute force attack detection using CloudTrail and Athena SQL queries
* Automated notification for alarms and alerts
* Exercise: Detecting IAM attacks in a simulated environment containing web application compromise and lateral movement

#### Malware Detection and Investigation on/for Cloud Infrastructure

* Quick Introduction to cloud infrastructure security
* Building clamAV- and Yara-based static scanner for S3 buckets, using AWS Lambda
* Building signature update pipelines using static storage buckets to detect recent threats
* Malware alert notification through SNS and slack channel
* Adding advanced context to slack notification for quick remediation
* Exercise: Simulating a malware infection in AWS and building an automated detection & alerting system

### Day 2

#### Threat Response and Intelligence Techniques on/for Cloud Infrastructure

* Integrating playbooks for threat feed ingestion and VirusTotal lookups
* Building a SIEM-like service for advance alerting and threat intelligence gathering using Elasticsearch
* Creating a Security datalake for advance analytics and intelligence search 
* Building dashboards and queries for real-time monitoring and analytics
* CTF exercise: Correlate multiple logs to determine the source of infection

#### Azure AD Attacks and Defenses

* Azure AD enumeration and permission gathering
* Privilege escalation and lateral movement through RBAC, service principals, etc.
* Auditing and logging in Azure 
* Detecting attacks through KQL queries

#### Forensic Acquisition and Analysis in the Cloud

* Building an IR 'flight simulator' in the cloud (AWS)
* Creating an API service for automated instance isolation and volume snapshots (AWS)
* Lambda functions to perform instance isolation and status alerts (AWS)
* Automating alert using Sentinel (Azure) for threat analysis
* Automating threat response through Azure Logic Apps  
* Implementing rulebook for cloud IR in an enterprise
* Enforcing security measures and policies to avoid instance compromise

#### Multi-Cloud Compliance

* Building a multi-cloud security assessment and monitoring strategy
* Automatic inventory and change detection in a multi-cloud environment
* Implementing compliance standards and benchmark standards (CIS) to the cloud environment

## Your Instructor

**Abhinav Singh** is a cybersecurity researcher with a decade-long experience working for global leaders in security technology, financial institutions and as an independent trainer/consultant. He is the author of Metasploit Penetration Testing Cookbook (first, second, and third editions) and Instant Wireshark Starter, both published by Packt. He is an active contributor to the security community in the form of patents, open-source tools, paper publications, articles, and blogs. His work has been quoted in several security and privacy magazines, and digital portals. He is a frequent speaker and trainer at eminent international conferences like Black Hat, RSA, and DefCon. His areas of expertise include malware research, reverse engineering, enterprise security, forensics, and cloud security.

