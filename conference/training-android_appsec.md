---
title: Classroom Training - Android AppSec in Practice
description: Pre-Conference Training Class, 2 September - OWASP New Zealand Day 2026

layout: conference/full-width
dataDir: conference-2026
sponsorsEventName: OWASP New Zealand Day 2026
---

[![Web Banner](/assets/images/2025_Banner_Graphic.jpg)](/conference/)   
[Back to Pre-Conference Training Page](training.md)
{: style="text-align: right; font-size: small;" }   
[Back to Conference Home Page](index.md)
{: style="text-align: right; font-size: small;" }   

# Android AppSec in Practice: Testing, breaking, and defending mobile apps

## One-Day Interactive (Classroom) Training - OWASP New Zealand Day 2026

## Course Details 

**Dates:** Wednesday, 2 September 2026

**Time:** 8:45 a.m. to 5:30 p.m. (NZST)

**Training Level:** Intermediate

**Instructor:** Shofe Miraz, [Cyber CX](https://cybercx.co.nz/){: target="_blank" }   

**Course Fee:** NZ $450.00 (plus GST and ticketing fees)

**Registration Site:** [https://events.humanitix.com/owaspnz2026-training](https://events.humanitix.com/owaspnz2026-training){: target="training-reg" }

## Course Description

Most Android security assessments follow a familiar script: decompile, grep for secrets, proxy traffic, bypass a local 
check. The most impactful findings are usually elsewhere: in where the app over-trusts the device, where the backend 
over-trusts the app, and where those boundaries quietly blur.

This one-day training takes a practical, AppSec-focused approach to Android testing. Starting from a lightweight 
threat model, attendees work through hands-on labs covering APK review, manifest analysis, local storage, WebViews, 
deeplinks, Frida-based runtime testing, and mobile API security.

For each area, we also cover the defensive side: common misconceptions, implementation pitfalls, what should be enforced server-side, what belongs on the device, and how teams can design safer mobile applications.

### Target Audience

AppSec engineers, web and API testers moving into mobile, security consultants, developers, and security champions 
responsible for Android applications.

No reverse engineering background required. Attendees should be comfortable with basic HTTP, proxy tools, the command 
line, and common web/API security concepts.

### Student Laptop Hardware/Software Requirements

* Bring a laptop capable of running the provided lab VM (Linux, prebuilt). 
* The VM includes all required tooling, vulnerable APKs, and lab exercises. 
* Shared, rooted Android devices will be available for hardware-based labs: Frida, app data extraction, proxying, WebView and deeplink testing, and client-side bypass exercises. 

### Topics Covered

#### Morning - The App and the Device (Local Attack Surface)

* The Mobile Attacker Mindset: 15-minute intro to the mobile attack surface
* Tearing Apart the App
* The Android Sandbox in Practice

#### Afternoon - The Bridge and the Runtime (IPC, WebViews, and Dynamic Analysis)

* Intro to Runtime Manipulation: Frida scripts, hooking basic Java methods
* WebViews & IPC: JavaScript bridge exposure and WebView configuration flaws
* Deeplinks: Trust boundaries and deeplink-to-WebView transitions

#### Late Afternoon and Take-Home: Advanced and Bonus Labs

* Network Interception: Network Security Config, proxying, TLS/certificate pinning
* Client-Side Bypasses: Root detection and emulator checks

## Your Instructor

**Shofe Miraz** is a Senior Security Consultant at CyberCX, specialising in mobile application security, reverse engineering, and security testing. He has presented at OWASP New Zealand Day on breaking mobile app defences with Frida and reverse engineering, and contributes to the OWASP New Zealand and Hack And Learn communities. 

His work covers Android testing, cross-platform mobile security, WebView attack surfaces, Frida-based runtime analysis, root/jailbreak bypasses, and mobile-to-API security. He brings that experience into labs that show what the design decisions behind those vulnerabilities actually look like in practice.
