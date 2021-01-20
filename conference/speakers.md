---
layout: default
title: Speakers and Abstracts
description: Presentation Abstracts and Speaker Biographies - 2021 AppSec NZ Conference
parent: Conference
grand_parent: Home
nav_order: 3
---

[![Web Banner](/assets/images/AppSecNZ_Web_Banner.png)](index.md)

[Back to Conference Home Page](index.md)
{: style="text-align: right; font-size: small;" }

# Presentation Abstracts and Speaker Biographies

## AppSec New Zealand Conference 2021

Presentations are listed on this page in alphabetical order by title.

-----------

### Anatomy of Automated Account Takeovers   
*Tal Eliyahu and Begum Calguner*   
Remote Presentation

#### Abstract

This presentation outlines the plenary mechanism of automated account takeovers (ATOs), while treating cybercrime as a fully functioning, profit driven business industry. Based on an extensive literature review, the paper analyses the constituent players and components of automated ATO attacks, their implications on the businesses, tech companies and victims, as well as the financial ramifications of the attacks.

#### Speaker Biographies

**Tal Eliyahu** - Tal is an operational security specialist with a proven track record in application and infrastructure vulnerability assessment and policy development holding OSCP, ISO 27001, 22301 and 22035 Certified Lead Auditor, and 27005 Lead Risk Manager certifications. With an academic background in software engineering and career path in various cybersecurity divisions, he has garnered expertise in diverse areas such as network and infrastructure penetration testing, vulnerability assessments, threat modeling at application, system and enterprise level, and providing risk/threat driven solutions.

**Begum Calguner** - Begum likens herself to Nathan Myhrvold, who describes himself 'I just have difficulty describing myself because the sort of things I do are unlikely enough that putting them together is credibility reducing.' She has experience as IT/IS analyst (ISO 27001 standards), in IT project management at enterprise and start up level, IT compliance, UX design and optimization, integration testing, financial analysis and business management addition to her academic background in mechanical engineering and finance.

-----------

### Are Your CI/CD Pipelines Secure?   
*Angel Rivera*   
Remote Presentation

#### Abstract

In this talk Angel will discuss common obstacles in securing applications, CI/CD pipelines, and protecting sensitive access to integration targets. Attendees will learn strategies to secure apps, sensitive data, integration points and improving pipeline security postures.

#### Description

Most CI/CD pipelines used by DevOps teams utilize integrations with services such as APIs, databases and other critical systems to complete their workflows. These integrations usually require the use of extremely sensitive secrets such as passwords, tokens or certificates and must be securely protected at all times. Unauthorized access to these pipeline secrets open these systems to threats from bad actors and illegal access of data.

In this talk. Angel will discuss common pain points in properly securing applications, CI/CD pipelines and protecting sensitive access gates to integration targets. Attendees will learn strategies to secure their applications, sensitive data and pipeline integration points. Attendees will leave with a better understanding of how to implement security layers that can improve their pipeline security posture.

#### Speaker Biography

**Angel Rivera** started his career as a US Air Force Space Systems Operations Specialist in Cape Canaveral AF Station, where he realized his passion for technology and software development. He has extensive experience in the private, public and military sectors and his technical experience includes military/space lift operations, technical writing, software development, SRE/DevOPs engineering. He also has a wealth of experience in defense and federal sectors such as contracting, information systems security and management.

You can usually find him speaking at or organizing local tech meetups and hackathons where he enjoys engaging with developers.

Angel's passions are positive disruption, learning, teaching, mentoring but most of all inspiring all forms of technologists and building awesome tech communities.

-----------

### "Better than Guessing": The Efficacy and Accuracy of SAST and SCA Tools   
*Raafey Khan - Datacom*

#### Abstract

You know that you should automate AppSec testing in your pipeline. At the very least, you should manually scan your code, but do the specific tools you use matter? Using the OWASP benchmark and our own apps, we'll compare the options and help you decide if the paid options are worth the money.

#### Description

The OWASP Benchmark Project is a Java test suite designed to evaluate the accuracy, coverage, and speed of automated software vulnerability detection tools. To enhance the picture the Benchmark provides, we've used open source and commercial Static Application Security Testing (SAST) as well as Software Composition Analysis (SCA) tools to scan a number of our own applications.

In this talk, we'll talk through: How SAST and SCA operate, and the various scanning techniques used by these tools How commercial SAST vendors fared against the OWASP benchmark, and whether the benchmark false positive rate results were in-line with the results of scanning our own apps How various commercial SCA options compare to the open source OWASP Dependency Check tool What value (beyond scan output) paid tools provide compared to their open-source counterparts.

#### Speaker Biography

**Raafey Khan -** An eternal security optimist (forgive him, he is young), Raafey has been helping organisations in NZ and the UK understand their cyber risk and why they should at-least try to embed security into their development processes.

As a founding member of Datacom's AppSec division, Raafey will attempt to do more of the same, with a real focus on automating everything and making security stupidly simple.

-----------

### Blame the Virus   
*Sarah Walker (Sera)*

#### Abstract

"The virus is the problem, not the people." Let's use New Zealand's response to COVID-19 as a perfect case study in blameless incident response.

#### Description

"The virus is the problem, not the people." New Zealand has had one of the harshest and arguably most effective responses to the pandemic globally. But with season 2 of lockdown kicking off, let's take a look at the public-facing response, and see what lessons the InfoSec industry can learn.

Our country's entire response team has been working hard not to place the blame on people, but on the virus. Messaging to the public has been timely, clear and concise. The focus is not on root cause, but on preventing further spread. And the underlying current to it all is "Be Kind."

In this talk we will examine NZ's fantastic example of a blameless incident review, and how we can replicate this when something happens to the systems we support.

#### Speaker Biography

**Sarah Walker (Sera)** is a reformed-developer-turned-SRE, currently working at a search solutions company. She has an advanced degree in logic which she primarily uses to win arguments on the Internet. She spends her time yelling at the cloud and hunting 9s, but now she's going to help you make your incident response process better.

Talk to her about cats, coffee, hoodies, fonts, or who is the best pony and why it is Twilight Sparkle.

-----------

### Bug Hunting with Static Analysis Tools   
*Moss Lilley - Xero*

#### Abstract

For security to keep up with the speed of development, we can no longer be gate keepers. This requires building secure defaults and enforcing them through automated checks.

The earlier developers know they've turned off a security control the better. We'll have a look into how we can provide feedback on this to developers in the IDE with a bit of **grep**. Grepping for bugs can return a lot of false positives, we'll have a look into using CodeQL to track user input into HTTP requests and *hopefully* find a SSRF in a web application.

#### Speaker Biography

**Moss Lilley** eats, breathes, sleeps.

He's been working at Xero for the last two years learning how to wrangle web apps and the cloud, trying to create secure defaults to keep pace with the speed of developers. He loves to hear about automating security, war stories and skiing.

-----------

### Building Better Security for Your API Platform using Azure API Management   
*Eldert Grootenboer*   
Remote Presentation

#### Abstract

This session will show how we can use Azure API Management to leverage better security for your APIs. Expect everything around hardening security of your services, with demos, best practices, and tips and tricks from the field.

#### Description

These days we use APIs to expose all our microservices , processes, and data, and all this while working in a PaaS or serverless environment. But how do we ensure this is done in a secure and governed way?

This is where Azure API Management comes in, where we can create a repository of all our APIs, and make sure to expose all of these securely in a standardized manner. In this session we will dive into the most common security hazards, and see how API Management helps us solve these. You will learn all about the strengths and weaknesses of the product, best practices, and how to harden the defenses of your services.

#### Speaker Biography

**Eldert Grootenboer** can be described as an Azure MVP, Cloud Solution Architect, blogger, public speaker and technical author. He can regularly be seen on conferences and user groups, speaking on Cloud related topics, with a strong focus on Azure. His experience with the Cloud comes from his daily work with these technologies in many innovative projects with various clients, as well as his drive to further dive into the latest developments in his spare time. Eldert enjoys sharing his knowledge with the community, and believes this is the best way to each other obtain more and better opportunities.

-----------

### Building purpleteam (a Security Regression Testing SaaS) - From PoC to Alpha   
*Kim Carter - BinaryMist*

#### Abstract

Developers / Engineers know that a build pipeline is an essential part of creating robust and reliable software, but what to put in it? This talk covers the creation of **purpleteam** from PoC to Alpha release, and why it's an ideal fit for the security regression testing slot of your build pipeline.

#### Description

Let me take you on the journey of trials, errors, and lessons learnt from getting a web app/API security regression testing proof of concept (PoC) to the next stage (alpha release).

In 2019, I gave a talk at OWASP New Zealand Day on a security regression testing PoC I had developed based on developer feedback. Since then, on top of a normal day job, I've been working on this project with every spare minute of time.

Let's walk through the: Architecture; Environments; Technologies; and Pressures.

We will then discuss the next steps for **purpleteam**, and how you can start using - and contributing to it if it's missing something you need.

#### Speaker Biography

**Kim Carter -** Technologist / Engineer, Information Security Professional, Entrepreneur and the founder of [BinaryMist Ltd](https://binarymist.io/). OWASP NZ Chapter Leader in Christchurch. Certified Scrum Master. Facilitator, mentor and motivator of cross functional, self managing teams. With a solid 19 years of commercial industry experience across many domains, Kim Carter enjoys teaching others how to apply information security to their Agile processes, bringing the security focus up front where it's the cheapest to implement, increasing profit and reducing costs. Co-founder of Christchurch Hacker Conference (CHCon), International trainer, speaker, published author, and Software Engineering Radio podcast host, focusing on:

* Software and network architecture;
* Web development and engineering; and
* Information security.

Kim is also a regular blog poster at [http://blog.binarymist.net](http://blog.binarymist.net). Kim loves designing and creating robust software and networks, breaking software and networks, then fixing them and helping organisations increase productivity.

-----------

### Camera Obscura   
*Tom Isaacson*

#### Abstract

There is a lot of concern about having cameras installed everywhere and governments or big companies using them to track us - invasion of privacy, tracking, release of personal details, blackmail, etc. But there are ways of implementing cameras for specific tasks that avoid these problems. I will talk about what these are, how they work and what their limitations are.

#### Speaker Biography

**Tom Isaacson** has been an embedded developer for 20 years. He hasn't bothered learning web development because he still thinks the internet is a passing fad, but he's been forced to think about security after his employer added networking to their products.

-----------

### DDoS: How can something so cheap be so expensive?   
*Jerome Van Rooijen - RedShield*

#### Abstract

Ransom notes, innovative attacks, stock exchanges being disrupted, spy agencies, war rooms...this sounds like a movie plot, not what you would expect to happen in New Zealand!

This talk covers a defenders experience and the lessons you can learn protecting a range of NZ financial institutions from an effective and sustained DDoS campaign. It will dive into the risks you face operating web facing services, the costs to run attacks, and what you can do to prepare for an attack and effectively defend yourself.

#### Speaker Biography

**Jerome Van Rooijen**'s day job is shielding the internet from bad guys&trade;. Previously network engineer, risk consultant, general infosec/risk peep. Always keen for fishing tips/trips.

-----------

### An Exploration of the Ethical Issues with the Gamification of Information Security Awareness Training   
*Conor Fitzgerald - Quantum Security*

#### Abstract

Gamification is the application of game-design elements and game principles in non-game contexts, such as information security awareness training. But, what are the ethical issues? Does gamification exploit, manipulate, harm or have a negative effect on employees? What are the InfoSec implications?

#### Speaker Biography

**Conor Fitzgerald** came to New Zealand in July 2019. He's Irish and works in information security with Quantum Security, out of Wellington.

-----------

### Federated Logins with OAuth 2, OpenID Connect, and JWTs   
*Matt Cotterell - ZX Security*

#### Abstract

Having a password for every website is falling out of fashion these days in favour of federated auth (like "Sign in with Facebook/Google"), but how does this work? In this talk, I will introduce how authentication, authorisation and credentials work using OAuth 2, OpenID Connect and JSON Web Tokens.

#### Description

Ever been frustrated with having to wrangle yet another password when you sign up for a new site? Ever felt uncomfortable because a website has asked for your banking password just so it can make a single transaction?

Web developers are quickly finding that using passwords for logins is falling out of fashion in favour of "federated" authentication. These are often quicker, safer and allow users to grant limited access to their stuff on other websites. This is often done using open standards such as **OAuth 2**, **OpenID Connect** and **JSON Web Tokens (JWTs)**.

In this talk, we will introduce how to authenticate users to your websites, apps, devices or even between servers using OpenID Connect, and authorise third-party access to some of their resources using OAuth 2. We will also discuss JSON Web Tokens (JWTs, confusingly pronounced "jots"), which we can use as temporary credentials to access APIs and verify identities.

#### Speaker Biography

**Matt Cotterell** is a Security Consultant and Software Engineer working for ZX Security in Wellington. His work involves breaking web applications, APIs and cloud configurations looking for security vulnerabilities. Beyond that, he enjoys exploring various authentication patterns and practices, software frameworks and public cloud providers in order to craft beautiful, secure and maintainable solutions to challenging technical problems.

In his spare time, he can be found watching bad movies, gleefully overusing the word "cyber," and feeling awkward writing biographies in a third-person perspective.


-----------

### The Five Stages of Security Grief: A Humorous Look at How We Can Help People Navigate the Realities of Information Security   
*Phil Howie - Onwardly*

#### Abstract

We will take a light-hearted tour through each of the five emotions people experience when facing security work - denial, anger, bargaining, depression and acceptance - and then offer some practical advice on how we can help them navigate through it and emerge out the other side successfully.

#### Description

People are often the most challenging aspect of information security. To implement effective security in an organisation, we must have everyone onboard. But the problem we face is non-security folks are often shocked by what needs to be done!

This talk is for anyone who is advocating or initiating security work within their organisation. Come along and hear a light-hearted take on the five stages of security grief people experience, and learn some practical things we can do to help our team mates navigate this journey with us.


#### Speaker Biography

**Phil Howie** is an Auckland-based developer, designer and newly-minted startup founder. He spent many years in the weeds with the technical aspects of building and securing web applications, and in more recent times has turned his focus to the human side of running startups. Phil is founder and CEO of the newly launched startup Onwardly, and is on a mission to make security more accessible and approachable for tech companies.

-----------

### Fuzzing: An Introduction to Fuzzing and How It Relates to App Security   
*Seth Berger - GitLab*

#### Abstract

How does a photo render your phone useless? How could one of the worst SSL vulnerabilities in history have been discovered years earlier, during initial development?

Learn what fuzzing is and learn about the tools and techniques used in fuzzing, and how it can be used to secure your applications.

#### Speaker Biography

**Seth Berger** is an engineering manager at GitLab, working on GitLab's DAST and fuzzing tools. Prior to GitLab, Seth has spent much of his career building software startups.

These days, he is energized to be focusing his time on building tooling to help developers secure their applications.

-----------

### Going Above and Beyond   
*Karan Sharma*

#### Abstract

While the OWASP Top 10 is a great baseline for WebApp security, I'd like to cover some of the attacks that aren't addressed there. These attacks are gaining lots of attention so it's time to shed some light on: HTTP Request Smuggling; JavaScript Prototype Pollution Attack; PostMessage Attack; and GraphQL API Hacking.

For each attack, we'll look at: the vulnerability that's being exploited; real-world exploit examples; mitigating controls; and lessons learned (where they have been).

#### Speaker Biography

**Karan Sharma** works as a pen tester for one of the leading telcos in New Zealand. He's been in the security industry for more than ten years. He has a true passion for breaking and fixing web and mobile apps. He enjoys doing web/mobile application security research in his free time and loves sharing his knowledge with others. If you want to shout things at him, he's @R00T on Twitter.

-----------

### Grow Your Own Security Cha-Cha-Champion   
*Toni James - SafeStack*

#### Abstract

Growing your own security champion is a lot like growing your own plant. It takes a great environment and a bit of care to make your team flourish. Toni will take you through some tips and tricks to grow your security garden, one champion at a time.

#### Speaker Biography

**Toni James** is a security consultant, software engineer, conference organiser, committee member, speaker, and diversity and inclusion advocate.

She's an avid snowboarder and mountain biker with her human and fur family in the Korowai mountains of New Zealand. You can find her running the Christchurch Hacker Conference, attending ISIG and Canterbury Tech meetups, or chatting with the Hacker Book Club crew. Twitter: [@_tonijames](http://twitter.com/_tonijames)

-----------

### A Hacker's View of DoS Attacks   
*Dave Robinson - ZX Security*

#### Abstract

DoS attacks are a topic at the front of a lot people's minds at the moment. This talk will examine how a hacker selects targets within an organisation, with a goal of causing the greatest business interruption.

Attackers can find juicy targets in more ways than you would initially think. A range of discovery techniques will be presented. People watching this talk will not be left hanging, as it will finish with how you can protect your assets from DoS attacks (Spoiler: a CDN, WAF, or DoS Scrubbing are not magical cures on their own).

#### Speaker Biography

**Dave Robinson -** In his time working in various parts of the IT industry, Dave/Karit has developed a skillset that encompasses various disciplines in the information security domain. Dave currently works as a Penetration Tester at ZX Security in Wellington and runs K&amacr;k&amacr;con.

Since joining ZX Security Dave has presented at DefCon, Kiwicon, Aerospace Village @ DefCon, BSidesCBR, ChCon, Unrestcon and at numerous local meetups; along with running training at Kiwicon, Syscan, CrikeyCon and TuskCon. He also has a keen interest in aerospace, lock-picking and all things wireless. Twitter: [@nzkarit](https://twitter.com/nzkarit) 

-----------

### How to Run an AppSec Program in an Agile Environment   
*Mert Can Co&scedil;kuner - Trendyol*   
Remote Presentation   

#### Abstract

This talk is about running an application security program in a business-first environment with Agile teams. It will introduce the challenges and solutions for how to develop application security strategy and improve developers' security maturity over time.

#### Description

Application security in an enterprise is a challenge. We can see this when we look at the statistics; There have been 16648 security vulnerabilities (CVEs) published by mid-December 2020 and the average severity is 7.1 out of 10. In this talk, you will find various solutions such as:

* Development team risk scoring based on maturity and business aspect;
* SAST/DAST at CI/CD pipeline, without blocking the pipeline itself;
* Bug bounty program;
* Penetration testing;
* Code review; and 
* Platform security developments to remove dependency on developers to implement features (e.g., internal authorization and secret management).

Most importantly, you will see the solutions has minimal friction to the teams, which creates a fine-tuned security program.

#### Speaker Biography

**Mert Can Co&scedil;kuner, MSc** is a Senior Security Engineer at Trendyol. He publishes a security blog at [mcoskuner.medium.com](https://mcoskuner.medium.com) and has spoken at various high end security events about red team, threat intelligence and malware analysis.

-----------

### The Incident Response Plan that Saved Christmas   
*Petra Smith - Aura Information Security*

#### Abstract

Incident response preparedness save time, money, stress...and maybe lives. This is the true story of my encounter with a deadly jellyfish, and how a well-defined Incident Response Plan saved the day.

#### Description

It's Christmas Day. You're floating serenely in the coral sea surrounding a real live tropical desert island...when, suddenly, you're having a too-close encounter with deadly wildlife. What do you do? Just follow your Incident Response Plan, of course!&dagger;

Don't have an Incident Response Plan? No worries. I'll take you through how to make a plan to help you navigate the shark-infested waters of a security incident with less stress, and get back to business - or living your best tropical mermaid life - quicker.

If your team's worst-case scenario plan is to hope it never happens, this talk is for you. I'll show you why you should prepare for the worst, and how anyone can make a plan that works.

&dagger; *Based on a true story*

#### Speaker Biography

**Petra Smith** is a professional opinion-haver and security culture specialist who is on a mission to make information security accessible to everyone. She has a point and she's getting to it.

-----------

### Let's Talk about Mental Well-Being in the Community   
*Hugh Davenport and Daniel Spector*

#### Abstract

This talk will discuss some soft skills and issues surrounding the need for awareness of mental wellbeing of people in the community. A lot of people suffer in silence. We would like to encourage this to be talked about!

#### Speaker Biographies

**Hugh Davenport -** Hugh is a Security Consultant, previously a developer. He has many years experience over many fields and has spoken at numerous conferences. Hugh also has suffered from depression and anxiety at times over the years.

**Daniel Spector -** *No biography provided*

-----------

### Leveraging OWASP Projects and Tools in Your AppSec Program   
*John DiLeo - Datacom*

#### Abstract

The Open Web Application Security Project (OWASP) boasts over 130 active Projects, whose volunteers have developed tools and resources covering nearly every aspect of application security and software assurance. The challenge lies in knowing what they are, where to find them, and how they can help.

John will present a brief overview of an array of interesting and useful OWASP Projects, including all of the current Flagship Projects, and provide insights into how each can be used to build and improve your AppSec program.

#### Speaker Biography

**Dr. John DiLeo** is the Auckland-area leader of the OWASP New Zealand Chapter. As a founding member of Datacom's AppSec Division, John heads up a consulting team that helps enterprises develop and mature their software assurance programs, with emphasis on governance, threat modelling and risk-based requirements, secure development practices, and security training.

Before specializing in application security, John was active as a Java enterprise architect and Web application developer. In an earlier life, he had specialized in developing discrete-event simulations of large distributed systems, in a variety of languages - including the Java-based language (FreeSML) he developed as part of his doctoral research.

In his "free time," John does a few things in the global OWASP community - he's a co-author of the OWASP Software Assurance Maturity Model (SAMM) v2.0, Co-Leader of the OWASP Application Security Curriculum Project, and Vice-Chair of OWASP's Training and Education Committee.

-----------

### Making Your Information Security Policy Useful   
*Stephen Coates - Aura Information Security*

#### Abstract

Trust me! Your information security policies suck. Nobody - even your auditor - wants to read through a piecemeal set of borrowed policy, written in the style of a wannabe lawyer from the 90's. Why can't we make them risk-based, referenced, well-structured, visually attractive, and in plain language?

#### Speaker Biography

**Stephen Coates** is a pragmatic consultant with many years of experience that cover information security, cloud, risk management, privacy, e-commerce, IT infrastructure, and IT Service Management. Having worked in these fields for so long, he has accumulated both a wealth of war stories (some experienced, some witnessed, and many near misses) and a treasure chest of badges and certifications.

-----------

### OWASP SAMM: Status and Roadmap   
*OWASP SAMM Project Team*

#### Abstract

The OWASP Software Assurance Maturity Model (SAMM) enables you to formulate and implement a strategy for software security that is tailored to the risk profile of your organisation. In this talk, we give an overview of the new release of the SAMM model. After 10 years since its first conception, it was important to align it with today's development practices. We will cover a number of topics in the talk:

* the core structure of the model, redesigned and extended to align with modern development practices;
* the measurement model, enhanced to cover both coverage and quality; and 
* the new security practice streams where the SAMM activities are grouped in maturity levels. 

We will demonstrate using the new SAMM2 Toolbox to measure the maturity of an example development team and how you can create a roadmap of activities.

Our new SAMM project "CI/CD" pipeline allows us to iterate much faster. We plan to push new SAMM improvements over the coming months. During this talk we will share our short-, medium-, and long-term plans for OWASP SAMM and hope to capture your feedback and requests for improvement.

#### Speaker Biography

Speaker TBC

-----------

### Payment Gateways: The Most Dangerous Game   
*Stephen Morgan - Datacom*

#### Abstract

Explore with me the exciting world of crypto, client tokens, and nonces through the lens of trust barriers and PCI compliance as we explore how these gateways can protect your card data from baddies and the e-commerce application itself. We will look at implementations from various popular providers, the implied history of cross-domain security on the internet, explain some of the traps developers fall into, and take a look into the future with Open Banking. Please leave your credit card at the door...

#### Speaker Biography

**Stephen Morgan** is now attempting to DevOps the raising of his having two children under two whilst working as a Security Consultant for a Professional Services company.

Stephen has worn many hats, he has been an impeccably witty: Penetration Tester, Dev(Sec)Ops engineer, Security Architect, and grumpy manager. His latest role sees him combining all four into a Megazord of Application Security within Datacom's new AppSec Division.

-----------

### Red vs. Blue: Which Grass Is Greener?   
*Kate Pearce and Chloe Ashford- Trade Me*

#### Abstract

Wherever you find yourself, we often find ourselves looking at the other "side" of security and wondering what it's like. In this session, we'll share some lessons from both sides of the fence. Is the grass really greener? Is that fake grass, carpet painted green, or...really impressive mould?

#### Description

There are many different parts to be played in security. It's easy to find yourself thinking someone else has it "easier" when they've really got their own set of challenges. The two of us went from the outside as Pen Tester and Auditor, to the inside as Head of Security and Assurance Lead - securing one of New Zealand's biggest online companies. We learned a whole lot along the way, about communication, motivation, technology, business, and ourselves.

We'll have stories from the outside, lessons from after, and tips for success. We'll pass some of what we've learned, and hopefully make you understand, and empathise with, those you interact with just a little bit better.

#### Speaker Biographies

**Kate Pearce -** Kate is Head of Security at Trade Me (which you may have heard of), where the security team runs to the mantra "safety at speed." Previously, she was a professional computer hacker (pentester) and has broken into everything from cars, to cellphone networks, to websites (which you may also have heard of - but she can't name!).

Kate has researched and presented on a bunch of other topics, including Multipath TCP, HTTP/2 & QUIC, Defensive Gaslighting, She also wears many other hats, such as being on the [NZITF](https://nzitf.org.nz) board and [Internet NZ](https://internetnz.nz) council.

**Chloe Ashford -** *No biography provided*

-----------

### Service Mess to Service Mesh   
*Rob Richardson*   
Remote Presentation

#### Abstract

In our quest to secure all the things, do we jump in too quickly? We'll use **Istio** and **Linkerd** as example service meshes, and look at the features we would expect from a service mesh. You'll leave with a concrete understanding of the service mesh, and be ready to justify the investment.

#### Description

In our quest to secure all the things, do we jump in too quickly? We'll use **Istio** and **Linkerd** as example service meshes, and look at the features we would expect from a service mesh. We'll dive into the day-one experience with both **Istio** and **Linkerd**, and some advanced scenarios of using the service mesh. 

We'll compare this to border security with an app gateway, and compare and contrast the security features, complexities, and implementation costs. You'll leave with a concrete understanding of the benefits and tradeoffs you get when you pull in a service mesh, and be ready to justify the investment.

#### Speaker Biography

**Rob Richardson** is a software craftsman building web properties in ASP.NET and Node, React and Vue. He's a Microsoft MVP, published author, frequent speaker at conferences, user groups, and community events, and a diligent teacher and student of high quality software development. You can find this and other talks on his blog at [https://robrich.org/presentations](https://robrich.org/presentations) and follow him on twitter at [@rob_rich](https://twitter.com/rob_rich).

-----------

### Taking a Preventative Human-Led Approach to Software Security and Embedding It into the Developer's DNA   
*Jaap Karan Singh - Secure Code Warrior*   
Remote Presentation

#### Abstract

The DevSecOps movement is here to change the game. The lines between AppSec and dev teams are increasingly blurred and more collaborative. Learn how developers can become a powerful piece of the DevSecOps pipeline, while upskilling & becoming an even more sought-after engineer in the process.

#### Description

The DevSecOps movement is here to change the game, creating an environment of shared responsibility for security, where developers become responsible for effective deployment, and the lines between AppSec and development teams are increasingly blurred and more collaborative. 

Jaap will demonstrate the changes the industry has faced in the journey from Waterfall to DevSecOps, as well as reveal how developers can become a powerful piece of the DevSecOps pipeline, without compromising the work they love most, all while upskilling and becoming an even more sought-after engineer in the process.

#### Speaker Biography

**Jaap Karan Singh** is one of the co-founders of Secure Code Warrior and our Senior Customer Success Manager. Jaap is an SME in all things Application security - past, present, and future trends. He has a strong background in development practices and cybersecurity initiatives. He works with some of the largest organisation in APAC to deliver succesfull Appliation Security/Secure Coding programs and has spoken at various Security workshops, seminars, and online events across the globe pushing for the message of security awareness to development communities and other Technology groups.

-----------

### Use the OWASP Threat Modeling Playbook to Improve Your Product Security   
*Sebastien (Seba) Deleersnyder - Toreon*   
Remote Presentation   

#### Abstract

We pulled together our threat modelling vision and strategy with OWASP best practices (like OWASP SAMM and the AppSec Champion Playbook) to create a 'Threat Modeling Playbook.' It shows you how to turn threat modelling into an established, reliable practice in your development teams.

#### Description

We consider threat modeling a foundational activity to improve your software assurance or product security.

We have trained hundreds of experts and consulted with as many clients regarding threat modeling. We found that a well-established threat modeling practice will measurably decrease security issues of delivered products.

Performing a threat modeling exercise is one thing. Scaling it up as a standard practice in an organization is another. Threat modeling is often considered a manual and costly activity with an unpredictable outcome.

We pulled together our Toreon threat modeling vision and strategy with OWASP best practices (like OWASP SAMM and the AppSec champion playbook) to create a 'Threat modeling playbook.' The playbook shows you how to turn threat modeling into an established, reliable practice in your development teams and in the larger organisation.

We released this as an open source OWASP project for everyone to use and improve upon. We encourage you to download and use our playbook. Try it with your own team or on a pilot project. And let us know how it works and how we can improve the playbook.

With you, we can create a community to support and continuously improve 'Threat modeling playbook.' Together, we can make threat modelling more widely available. This in turn will make all of our software more secure.

* GitHub Repository: [https://github.com/Toreon/threat-model-playbook](https://github.com/Toreon/threat-model-playbook)
* OWASP Project Page: [https://owasp.org/www-project-threat-modeling-playbook/](https://owasp.org/www-project-threat-modeling-playbook/)

#### Speaker Biography

**Sebastien (Seba) Deleersnyder** is co-founder and CEO of Toreon and a proponent of application security as a holistic endeavour. He started the OWASP Belgium chapter, has been a member of the OWASP Foundation Board, and has given numerous public presentations on Application Security. Seba also co-organized the yearly security & hacker BruCON conference and training events in Belgium.

With a background in development and many years of experience in security, he has trained countless developers to create software more securely. He has led OWASP projects such as OWASP SAMM, thereby truly making the world a little bit safer. Now he is adapting application security models to the evolving field of DevOps and is also focused on bringing Threat Modelling to a wider audience. Twitter: [@sebadele](https://twitter.com/Sebadele)

-----------

### Using an Agreed Scale of Business Harm to End Security Arguments   
*Stephen Coates - Aura Information Security*

#### Abstract

How can you say you have a risk programme in place for information security without a pre-agreed scale of business harm? Publish the scale and watch security arguments disappear like magic! It can be a simple one-pager with rows for key stakeholders and 4 to 6 columns for the business impact.

#### Speaker Biography

**Stephen Coates** is a pragmatic consultant with many years of experience that cover information security, cloud, risk management, privacy, e-commerce, IT infrastructure, and IT Service Management. Having worked in these fields for so long, he has accumulated both a wealth of war stories (some experienced, some witnessed, and many near misses) and a treasure chest of badges and certifications.

-----------

### Vulnerability Management 101 with OWASP DefectDojo   
*Rohit Sharma*

#### Abstract

Numerous public reports show 2020 as the "worst year ever" for data breaches, with a common source being web applications with unpatched vulnerabilities. We will present vulnerability management using OWASP DefectDojo and how we leverage it to protect New Zealand health organisations and beyond.

#### Description

Numerous public reports found 2020 to be the "worst year ever" for data breaches, and with healthcare standing at the forefront during the COVID-19 pandemic response, and rapid digital transformation of healthcare, it is natural the cybersecurity risks will increase and affect healthcare organisations and beyond.

We looked at ways to reduce the attack surface and incident rates of health organisations experiencing security challenges and lack of funding to address this. One of the most common reasons for data/system breaches at small-to-medium organisations is that the vulnerabilities present in their web applications were discovered and exploited by threat actors. For example, the cause of TuOra Compass Health's cybersecurity incident in late 2019 was the exploitation of publically known web server vulnerabilities. 

This presentation will give a brief overview of why web application vulnerability management solutions are essential nowadays; how we leveraged OWASP DefectDojo, cloud infrastructure, and docker containers to build our CyberScan continuous vulnerability management system; how we automate, discover, triage and track vulnerabilities across multiple New Zealand health organisations, teams, and services; and our lessons learned.

#### Speaker Biography

**Rohit Sharma** - *No biography provided*

-----------

### Web Apps: Hardening Too Hard?   
*Nick Lauder - Quantum Security*

#### Abstract

This talk aims to tackle the low hanging fruit of penetration testing. Identifying those issues that consistently appear and figuring out why they never get fixed. I am hoping to show developers and consultants how simple the fixes can be, while also demonstrating the impact of improper configurations.

#### Description

Almost every web application has these issues: 

* Weak TLS Configuration 
* Lack of Security Headers 
* Version Number Disclosure 
* Exposed Administration Portal 
* Sequential Object Identifiers 
* Lack of CSRF Tokens 
* And on and on and on...

Why are they always here? What is so bad about them? Why should I bother fixing them?

Nick will go over these issues and demonstrate how easy they can be to fix, but also the ways they can break your app. Using the experience of having his colleagues bully every web application he puts together, Nick will talk about the balance that can be found between security and functionality.

The aim is to have a hardened web application, no availability compromises, and really make those penetration testers work for their findings.

#### Speaker Biography

I'm **Nick Lauder**, the long term "intern" at Quantum Security, based in Wellington. I am a software engineer with a passion for electronics and somehow ended up in security. Besides introducing memes and youth slang to the office, I make and break web apps. Outside of work you'll find me at the pub, snowboarding, or breaking collar bones, all while managing to annoy my boss.

-----------

### XXE: Why It's Still in the [OWASP] Top 10   
*Sam Shute - Quantum Security*

#### Abstract

XXE is commonly passed over in normal teaching and educational conference talks, but remains one of the top vulnerabilities for web servers that utilize XML parsers. Recently, we have still been finding applications vulnerable to XML Entity attacks, which this talk will cover in an easy to understand way.

#### Description

XML External Entities (XXEs) have been in the OWASP Top Ten since 2017, however they have existed as a vulnerability class for approximately two decades. Entities within XML can be used to do lots of fun things as an attacker, such as causing a Denial-of-Service, stealing files, or even creating a backdoor.

This talk will cover the basics of what XXEs are, how to exploit them, and importantly for developers, how to prevent them.

#### Speaker Biography

**Sam Shute** is a Principal Security Consultant with Quantum Security in Wellington. His day-to-day work revolves mostly around running Quantum's technical consulting team, but occasionally he gets out of the office to compromise applications and networks all around New Zealand.

Sam's other areas of interest include network penetration testing, 3D printing, and lock picking.

-----------

### Your Browser Wants You to Be Secure   
*Kirk Jackson - RedShield*

#### Abstract

Web browser developers now work hard to keep your users and your applications secure. We'll discuss the state-of-the-art defences provided by web browsers, and explain how you can incorporate them into your web applications. You will learn how to fairly easily improve the security of your apps.

#### Description

The makers of Chrome, Firefox, Internet Explorer, and other browsers are constantly pushing the envelope in browser security, with new features recently released and under development. Many of these features are simple to incorporate into your application, and this talk will help you keep up with the moving target of staying safe on the Internet.

Over the past 10 years there have been numerous HTTP headers, sandboxing and protection mechanisms added to browsers - so many that it's hard to keep up! It's possible that the best defences you learned in 2011 have been bettered by the new stuff rolling out each month in 2021.

In this talk you'll learn about the old, with a focus on the new and shiny. We will focus on those protections that are available now, and proven by others to work - and have a quick point towards future security enhancements that are coming in the future.

#### Speaker Biography

**Kirk Jackson** works at RedShield, leads the OWASP Wellington Meetup, and has previously helped organise the annual OWASP NZ Day in Auckland.

Kirk worked as a web developer before switching to the defence team - setting up Xero's security practice, working as a pen tester, and in defence roles at several companies.

-----------

### Zero to OSCP   
*Moss Lilley - Xero*

#### Abstract

Everyone has a different story of how they got into Cyber Security. As a student, my impression came straight out of Hollywood with dark rooms and green text rushing down monitors. In this talk I'll pull back the curtain and share my experience getting into the Cyber Security field.

#### Description

With Hollywood fantasizing *hackers* as computer wizards, overloading mainframes and bypassing CPUs, what your average person working in the Cyber Security industry gets up to in the 9-to-5 is shrouded.

In this talk I'll give a fresh take on what it's like getting into Cyber Security. Sharing my experience growing up in a parental controls war for more time on the internet, that one security paper I took at uni, flinging out CVs, convincing someone to give me a job, finding out what a blue team does, studying for my OSCP, and dealing with burnout.

#### Speaker Biography

**Moss Lilley** eats, breathes, and sleeps.

He's been working at Xero for the last two years, learning how to wrangle web apps and the cloud to try create secure defaults to keep pace with the speed of developers. He loves to hear about automating security, war stories and skiing.

-----------

