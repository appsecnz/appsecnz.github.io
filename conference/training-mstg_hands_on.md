---
layout: conference-2022/full-width

title: Online Training - MSTG Hands-On
description: Pre-Conference Training Class, 5-6 July - OWASP New Zealand Day 2022 
---

[![Web Banner](/assets/images/2022_Banner_Graphic.jpg)](/conference/)   
[Back to Pre-Conference Training Page](training.md)
{: style="text-align: right; font-size: small;" }   
[Back to Conference Home Page](index.md)
{: style="text-align: right; font-size: small;" }   

# Mobile Security Testing Guide Hands-on

## Two-Day Interactive (Online) Training - OWASP New Zealand Day 2022

## Abstract

How to bypass SSL Pinning on a Flutter app or how to bypass FaceID on a non-jailbroken device? All of this - and more - will be covered in this two-day hands-on course. Students will have time to exploit real-world mobile apps and vulnerabilities in apps created by the trainers themselves.

## Course Details 

**Dates:** Tuesday and Wednesday, 5-6 July 2022

**Time:** 8:45 a.m. to 5:30 p.m. (NZDT)

**Instructor:** Sven Schleier, Co-Leader, OWASP MSTG Project   

**Course Fee:** NZ $900.00 (plus GST and ticketing fees)

**Registration Site:** [https://events.humanitix.com/owaspnz2022-training](https://events.humanitix.com/owaspnz2022-training)

## Target Audiences

This course is developed for:

* Penetration Testers who want to achieve full coverage when testing a mobile app
* Developers who want to understand how attacks can be executed against their mobile apps
* Security Auditors who want to know how to work with an accepted industry standard for mobile security 
* Internal Awareness Teams / Trainers, to communicate the latest mobile attacks and vulnerabilities to their students
* Information Security personnel, interested in defending and attacking Android and iOS 
* Anyone interested in learning more about mobile attacks

## Course Description

Many people that are either protecting or attacking mobile apps, have a background in network and web application security, a quality that is valuable for mobile app security. Nevertheless, not everything can be mapped 1:1 to the mobile world. The impact of vulnerabilities we know from web applications will be different in the context of mobile apps. A reflected Cross-Site Scripting is pretty hard to exploit if there is no webview used in the app. Achieving a man-in-the-middle position between a mobile app and an API has additional hoops to jump through, like bypassing of SSL Pinning or reconfiguring the Network Security Configuration on Android.

At the beginning of the first day, we will cover all of these mobile security basics by going through the OWASP Mobile Security Testing Guide (MSTG) and the OWASP Mobile AppSec Verification Standard (MASVS), which builds the foundation for the course. We will then quickly start with Android, by giving an overview of the Android Platform and its security mechanisms. After spinning up the customized Android instance in the cloud and creating an environment for testing Android apps, we are covering different topics and techniques which will include:

* Function Hooking in Hybrid app frameworks (Flutter) to reverse engineer a custom Keystore implementation and bypass SSL pinning
* Identifying and exploiting a real word deeplink vulnerability
* Smali Patching and Application repackaging
* Introduction to Dynamic Instrumentation with Frida to
    * break end-to-end encryption with Brida (Burp and Frida)
    * bypass Frida detection mechanisms
    * bypass multiple root detection mechanisms

On day two, we'll focus on iOS and will begin with an overview of the iOS Platform and Security Architecture (Hardware Security, Code Signing, Sandbox, Secure Boot, Security Enclave etc.). After explaining IPA container and the iOS file system structure we start creating an iOS testing environment and deep dive into various topics and techniques, including: 

* Analyze iOS applications that use non-HTTP traffic
* Bypassing SSL Pinning with SSL Kill Switch and Objection
* Showcasing different implementations of Touch ID / Face ID and ways to bypass them
* Demonstration of Testing without Jailbreak by repackaging an IPA with Frida through Objection
* Using Frida for Runtime Instrumentation and patching of iOS Apps to 
    * Bypass Anti-Jailbreaking Mechanisms 
    * Bypass Debugging detection

After successful completion of this course, students will have a better understanding of how to test for vulnerabilities in mobile apps, how to mitigate them and how to execute tests consistently. The course is based on the OWASP Mobile Security Testing Guide (MSTG) and is conducted by one of the author himself. The OWASP MSTG is a comprehensive and open-source guide about mobile security testing for both iOS and Android. A physical copy of the latest MSTG release will be provided, which students will be able to keep and take home.

## What You'll Receive

* PDF copies of all presentation slides
* IPA/APKs of vulnerable apps
* Pre-configured virtual machine, for use in the training

## What You'll Need to Have

The following prerequisites need to be fulfilled by the students in order to be able to follow all exercises and fully participate:

* Laptop (Windows/Linux/macOS) with at least 8 GB Ram and 40GB of free disk space
* Full administrative access, in case of any issues with the laptop environment (e.g. deactivate AV or Firewall)
* Virtualization software (e.g. VMware, VirtualBox); A VM will be provided as OVA with all tools needed for the training
* Stable Internet connection with at least 50 Mbps bandwidth

An Android hardware device is **not** needed by the participants. The Android hands-on exercises of the training will instead be executed in a cloud-based virtualized environment that allows attendees to access a rooted Android device during the training. One Android instance will be provided for each participant.

An iOS device is also **not** needed, as an iOS emulator will be provided for each student that is hosted in Corellium. This is also a cloud-based environment that allows each student access to a jailbroken device during the training.

## Course Topics

**Day One: Android**

* Module 1: Overview of Android Platform and Security Mechanisms:
    * Android Security Architecture (Bootloader, Permission model, Sandboxing etc.)
    * App Communication with the Operating System (IPC, Intent etc.)
    * Runtime Environment (Dalvik vs. ART)
* Module 2: Creating an Android Testing Environment
    * Android Debug Bridge (ADB)
    * Setting up an Android Genymotion instance in the cloud for testing
    * Differences and limitations between testing in an emulator/simulator and a physical device
* Module 3: Android Application Structure
    * Decompiling an APK
    * APK file structure
    * Understanding and analyzing AndroidManifest.xml
* Module 4: Static Analysis
    * Identifying a Deep link vulnerability in a Kotlin App
    * Exploiting the Deep link vulnerability
    * Automated Static Analysis with MobSF; showing quick wins and it’s limitations to identify the Deep link vulnerability
* Module 5: Intercept Network Traffic
    * Introduction into a methodology to intercept all network traffic of a mobile app and analyze with Burp Suite
    * Analyzing apps build on frameworks that are not using the system Proxy; Students will be intercepting an app build with Flutter
    * Analyzing all outgoing (non-HTTP) traffic on the Android device, by chaining tcpdump, netcat, adb and Wireshark together
    * Piping network traffic from an Android device to your laptop through USB by using adb reverse, e.g. in case of client isolation in the WiFi network
    * Repackaging and analyzing an app with Network Security Configuration
* Module 6: Dynamic Instrumentation 101 Android
    * Introduction into Frida and its basics (hooking, overloading, usage of Frida CLI and Frida scripts, etc.)
    * Identify and hook functions of an Android App
    * Using Frida Server on a rooted device
* Module 7: Bypassing Root detection
    * Introduction into various ways of implementing root detection
    * Using Dynamic Instrumentation to bypass multiple root detection functions and compare it to other techniques, such as patching Smali and using Xposed (Pros/Cons)
* Module 8: Testing for Sensitive Data in Local Storage (Shared Preferences, SQLite Databases, Internal and External Storage) and secure usage of KeyStore
* Module 9: Hands-on: Android Reverse Engineering
    * Bypass detection mechanisms for Dynamic Instrumentation (Frida)
* CTF: Investigate an app with your newly acquired skills and win a prize!

**Day Two: iOS**

* Module 1: Overview of iOS Platform and Security Mechanisms
    * iOS Security Architecture (Hardware Security, Code Signing, Sandbox, Secure Boot, Security Enclave)
    * Explaining IPA Container and Structure on the iOS File System
* Module 2: Creating an iOS Testing Environment
    * Testing with and without Jailbreak and it’s limitations
    * Testing in an emulator compared to a real device
    * Setting up the iOS device in Corellium
    * Describing various ways of installing iOS Apps
* Module 3: Demonstration of testing iOS Apps without Jailbreak:
    * Repackaging an IPA with the Frida Gadget by using Objection
    * Overview of Objection and it’s limitations
* Module 4: Static Analysis
    * Decrypting an app with Fairplay Encryption by using clutch or frida-ios-dump
    * Using class-dump
    * Automated Static Analysis with MobSF
    * App Transport Security (ATS)
* Module 5: Dynamic Instrumentation 101 (iOS)
    * Recap of Frida and its basics (hooking, overloading, usage of Frida CLI and Frida scripts, etc.)
    * Identify and hook functions of an iOS App
    * Using Frida for testing iOS Apps
    * Using Frida Server on a jailbroken device
* Module 6: Dynamic Analysis
    * Introduction into a methodology to intercept all network traffic of a mobile app and analyze with Burp Suite
    * Piping network traffic from an iOS device to the laptop via USB by using usbmuxd
    * Analyzing traffic through a remote virtual interface (rvi)
    * Intercepting apps build on frameworks that are not using the system Proxy (Flutter)
    * Lab to intercept non-HTTP traffic
* Module 7: Bypassing SSL Pinning
    * Identifying usage of SSL Pinning
    * Lab to show different ways of bypassing SSL Pinning, by using SSL Kill Switch (jailbroken device) and by using Objection (non-jailbroken device)
* Module 8: Testing for Touch ID /Face ID Bypass
    * Overview of Touch ID / Face ID functionality and implementations
    * Lab to bypass Biometric authentication through Objection
* Module 9: Testing for Sensitive Data in Local Storage
    * Explanation of different ways to store data on iOS (Core Data, Plist, Sqlite…) and how to store it securely by using the Keychain
    * Lab to analyze local storage by using Objection and Grapefruit
* Module 10: Hands-on: Reverse Engineering
    * Basic Reverse Engineering of an iOS app
    * Bypassing Client-Side Security controls such as jailbreak detection through dynamic instrumentation with Frida
* CTF: Investigate an app with your newly acquired skills and win a prize!

## Your Instructor

**Sven Schleier**

**Sven** is the Technical Director of F-Secure Singapore and has hands-on experience in attacking and defending web and mobile apps for the last 10+ years. He became specialised in Application Security and has supported and guided software development projects for Mobile and Web Applications during the whole SDLC.

Besides his day job, since 2016, Sven has been one of the core project leaders and authors of the OWASP Mobile Security Testing Guide (MSTG) and OWASP Mobile Application Security Verification Standard (MASVS) and has created the OWASP Mobile Hacking Playground. Sven gives talks and workshops about Mobile Security worldwide to different audiences, ranging from developers to students and penetration testers.
