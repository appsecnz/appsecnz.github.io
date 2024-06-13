---
title: Classroom Training - Introduction to Android Application Penetration Testing
description: Pre-Conference Training Class, 3-4 September - OWASP New Zealand Day 2024 

layout: conference/full-width
dataDir: conference-2024
sponsorsEventName: OWASP New Zealand Day 2024
---

[![Web Banner](/assets/images/2024_Banner_Graphic.jpg)](/conference/)   
[Back to Pre-Conference Training Page](training.md)
{: style="text-align: right; font-size: small;" }   
[Back to Conference Home Page](index.md)
{: style="text-align: right; font-size: small;" }   

# AI SecureOps: GenAI and LLM Security for Enterprises

## Two-Day Interactive Online Training - OWASP New Zealand Day 2024

## Abstract

Hands-on experience in GenAI and LLM security through CTF-styled training, tailored to real-world attacks and defense scenarios. Dive into protecting both public and private LLM solutions, crafting specialized models for distinct AI security challenges of red and blue teams.

## Course Details 

**Dates:** Tuesday and Wednesday, 3-4 September 2024

**Time:** 8:45 a.m. to 5:30 p.m. (NZST)

**Instructors:** Abhinav Singh)   

**Course Fee:** NZ $900.00 (plus GST and ticketing fees)

**Registration Site:** [https://events.humanitix.com/owaspnz2024-training](https://events.humanitix.com/owaspnz2024-training){: target="training-reg" }

## Prerequisites - What Students Should Bring, and do before class

* Familiarity with AI and machine learning concepts is beneficial, but not required   
* Ability to run python codes and notebooks   
* Familiarity with common GenAI applications like OpenAI   
* Complete the pre-training setup (instructions will be provided closer to the date) before the first day   
* A laptop with Internet access, and the following items configured (following the setup instructions):   
    * API keys for OpenAI, Langchain, Anthropic   
    * Access to AWS and Azure accounts   
    * Google Colab and AWS Sagemaker   
    
## What Students Will Be Provided

* One year access to a live interactive playground, with various exercises to practice different attack and defense scenarios for GenAI and LLM applications   
* "AI Guardian" Metal coin for CTF players   
* Complete course guide containing 200+ pages, in PDF format, containing step-by-step guidelines for all the exercises, labs, and a detailed explanation of concepts discussed during the training   
* PDF versions of slides that will be used during the training   
* Access to Slack channel for continued engagement, supportand development   
* Access to Github account for accessing custom-built source codes and tools   
* Access to HuggingFace models, datasets, and transformers   

## Outside Work - Homework to be completed between Day 1 and Day 2

At the end of Day 1, students will be asked to implement a small exercise involving training a base model with sample custom data provided to them. The model's training takes a while, so it will be assigned as a take-home task.

## Course Description

By 2026, Gartner, Inc. predicts that over 80% of enterprises will engage with GenAI models, up from less than 5% in 2023. This rapid adoption presents a new challenge for security professionals. To bring you up to speed, this training provides essential GenAI and LLM security skills through an immersive CTF-styled framework. Delve into sophisticated techniques for mitigating LLM threats, engineering robust defense mechanisms, and operationalizing LLM agents, preparing them to address the complex security challenges posed by the rapid expansion of GenAI technologies. You will be provided with access to a live playground with custom built AI applications replicating real-world attack scenarios. The course focuses on safeguarding both public GenAI services and proprietary enterprise LLM solutions. You will dive deep into creating specialized models to tackle unique security issues and also to deploy defense strategies across GenAI supply chain, utilizing both open-source and custom tools. This dual approach ensures comprehensive coverage of "securing GenAI technologies" alongside "leveraging GenAI for enhancing security." Mastering these two dimensions is crucial for developing sophisticated defense infrastructures in enterprise environments. This training will also cover the completely new segment of ethics and trustworthiness in GenAI services. Unlike traditional cybersecurity verticals, these unique challenges such as bias detection, managing risky behaviors, and implementing mechanisms for tracking information are going to be the key challenges for enterprise security teams. The sections will explore complex scenarios related to access rights and data privacy protection, ensuring secure usage of sensitive data in LLM application development(practical labs).

By the end of this training, you will be able to:   

* Red-team a GenAI application using adversary simulation, LLM top 10 and MITRE Atlas frameworks, and apply AI security and ethical principles in real-world scenarios   
* Execute, and defend against, adversarial attacks, including prompt injection, data poisoning, model inversion and more   
* Perform advance AI red-teaming through multi-agent based auto-prompting attacks   
* Build LLM security scanners to protect injections, manipulations, and risky behaviors in LLMs   
* Develop and deploy enterprise-grade LLM defenses, including custom guardrails for input/output protection, benchmarking models for security and pen-testing of LLM Agents   
* Implement Retrieval Augmented Generation(RAG) to train custom LLM agents and solve specific security challenges, such as building security operations co-pilot, cloud policy generator, compliance automation and much more   
* Use open-source tooling, HuggingFace, Langchain, OpenAI, NeMo, Ollama, Streamlit and much more to craft your own tools and get up to speed with GenAI development   
* Utilize cloud based GenAI services like AWS Bedrock and Azure OpenAI as the playgrounds for learning and development   
* Utilize base models like LLaMA, GPT4, and Claude. Deploy them locally or in cloud to build Retrieval augmented Training for faster retrieval of information from custom datasets   
* Establish a comprehensive LLM SecOps process(assisted through GenAI), to secure the supply chain against adversarial attacks and perform a comprehensive threat model of enterprise applications.

### Topic Outline

#### Introduction

* Introduction to LLMs and GenAI    
* LLM and GenAI terminologies and architecture   
* Technology use-cases   
* Agents, multi-agents and multi-modal models  

#### Elements of AI Security

* Understanding AI vulnerabilities with case studies on AI security breaches    
* Application of Security   
* Deploying and running LLM model locally   
* Principles of AI ethics and Safety. - OWASP LLM top 10   
* MITRE mapping of attacks on GenAI Supply chain   
* Prompt Generation for solving specific security cases   
* Build defense against local and global models

#### Adversarial LLM Attacks and Defenses

* Direct and Indirect Prompt Injection attacks   
* Advance prompt injections through obfuscation and cross-model injections   
* Breaking instruction boundaries and trust criteria   
* Advance LLM red teaming: Automating multi-agent conversation to prompt inject models at scale   
* Attacking LLM Agents for task manipulation and risky behavior   
* Adversarial examples, training data extraction, model extraction, and data poisoning   
* Attack mapping through LLM top 10 and MITRE Atlas frameworks   
* Defense automation through prompt output validation using GenAI as well as static lists   
* Benchmarking LLMs from generating insecure code or aid In carrying out cyber attacks

#### Building Enterprise-Grade LLM Defenses

* Deploying LLM Security scanner, adding custom rules, prompt block lists, and guardrails   
* Writing custom detection logic, trustworthiness check and filters   
* LLM Guard for protecting input and output   
* Protecting RAG enabled GenAI agents from emitting sensitive data and confidential internal data   
* Attack simulation and defense use-cases against financial fraud and agent manipulation   
* Building security log monitoring & alerting for models using open source tools   
* LLM Security Benchmarking and continuous reporting

#### Building LLM Agents for Security Use Cases

* Natural language processing-based Security Copilot bot, trained on custom log data   
* IAM policy generator, bot trained on over 5000 policies across different cloud environments   
* Security operations assistant bot using custom data and no-code platforms

#### Building LLM and GenAI SecOps Processes

* Summarizing the learnings into building SecOps process   
* Monitoring trustworthiness and safety of enterprise LLM applications   
* Implementing NIST AI Risk management framework(RMF) for security monitoring   

## Your Instructors

**Abhinav Singh**  is an esteemed cybersecurity leader and researcher with more than a decade of experience across technology leaders, financial institutions, and as an independent trainer and consultant. Author of "Metasploit Penetration Testing Cookbook" and "Instant Wireshark Starter," his contributions span patents, open-source tools, and numerous publications. 

Recognized in security portals and digital platforms, Abhinav is a sought-after speaker and trainer at international conferences like Black Hat, RSA, DEFCON, BruCon and many more, where he shares his deep industry insights and innovative approaches in cybersecurity. He also leads multiple AI security groups at CSA, responsible for coming up with cutting-edge whitepapers and industry reports around safety and security of GenAI.
