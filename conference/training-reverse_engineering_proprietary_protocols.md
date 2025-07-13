---
title: "Classroom Training - Reverse Engineering Proprietary Protocols"
description: Pre-Conference Training Class, 2-3 September - OWASP New Zealand Day 2024

layout: conference/full-width
dataDir: conference-2025
sponsorsEventName: OWASP New Zealand Day 2025
---

[![Web Banner](/assets/images/2025_Banner_Graphic.jpg)](/conference/)   
[Back to Pre-Conference Training Page](training.md)
{: style="text-align: right; font-size: small;" }   
[Back to Conference Home Page](index.md)
{: style="text-align: right; font-size: small;" }   

# Reverse Engineering Proprietary Protocols

## Two-Day Interactive (Classroom) Training - OWASP New Zealand Day 2025

## Abstract

Protocol Reverse Engineering (PRE) recovers specifications of undocumented protocols. It’s crucial for analyzing malware and enhancing IDS. This training covers PRE principles, writing protocol dissectors, and fuzzing for vulnerabilities, using tools like Scapy and Boofuzz.

#### Target Audience

1. DFIR practitioner - to investigation malicious activity in the network
1. Reverse Engineer - write a custom client that fully replicates the existing client software/game.
1. Bug Hunter - Write protocol fuzzer for Black Box testing for application processing remote data, for example, lots of IoT Devices use custom protocol for efficient communication.
1. Malware Analyst - To decode C&C server commands and the data which is exfiltrated
1. Threat Hunting - write network signatures for new emerging APT threats or it could be an intruder in your network, this course will help you decode network and analyze network traffic.
1. Developers - who don’t have access to source code or protocol documentation, it usually happens when you are dealing with a legacy system which is too old and the company cannot find any documentation and you intend to migrate the system to new technology.
1. While debugging software over the network, writing a protocol dissector can help you to get a deeper understanding of network communication done by your software.
1. Helps you to do network debugging/diagnostics of application layer data.
1. It helps you understand what is really transmitted over the network.
1. RED Team - take advantage of what the Security Operation Center (SOC) doesn’t know. Look for data leaks, do attacks like inject, replay and spoofing.
1. Vulnerability Researcher/Exploit Developer - this will also help exploit developer and vulnerability research to reproduce remote vulnerability and find zero-day bugs.

## Course Details

**Dates:** Tuesday and Wednesday, 2-3 September 2025

**Time:** 8:45 a.m. to 5:30 p.m. (NZST) each day

**Instructor:** Munawwar Hussain Shelia (Vulnerability Researcher, Qualcomm)

**Course Fee:** NZ $1,000.00 (plus GST and ticketing fees)

**Registration Site:** TO BE OPENED SOON.

{% comment %}
[https://events.humanitix.com/owaspnz2025-training](https://events.humanitix.com/owaspnz2025-training){: target="training-reg" }
{% endcomment %}

**Maximum Enrolment:** 50 attendees

## Prerequisites

* Knowledge of security concepts
* Basic understanding of networking concepts
* Knowledge of Linux OS
* Basic Python programming language

## What Students Should Bring and Do Before Class

* Laptop with at least 50 GB free space
* 8+ GB minimum RAM (4+GB for the VM)
* External USB access (min. 2 USB ports)
* Administrative privileges on the system
* Virtualization software – Latest VirtualBox (5.2.X) (including Virtualbox extension pack)
* Virtualization (Vx-t) option enabled in the BIOS settings for VirtualBox to work

## What Will Students Be Provided With

* Virtual Machine with all the needed software pre-installed.
* Training Material/slides.
* Lab Manual.

## Course Description

A network protocol deﬁnes the format and semantics of message exchange between applications. In modern times there are a myriad of proprietary application protocols like Skype Protocol, Dropbox Protocol, etc which applications use to achieve various goals like bandwidth eﬃciency, custom encryption/compression, etc. These protocols could have security vulnerabilities. Protocol Reverse Engineering (PRE) is not only useful for oﬀensive purposes but also used by modern Intrusion Detection Systems(IDS), they use the knowledge of protocol speciﬁcation to do Deep Packet Inspection(DPI) which can enhance its capabilities, where it earlier relied just based on pattern matching which may produce lots of false positives. Custom protocols are not only used by legitimate applications but also by malware and botnets like Zeus, Emotet, etc. By reversing malware protocol you can connect to malware servers and track their campaigns.

Protocol Reverse Engineering(PRE) is an art and science of recovering the protocol speciﬁcation of the obscure/proprietary protocol whose documentation is unavailable or poorly documented. There are eﬀorts to develop automated PRE tools but they are largely academic and are not mature enough to be usable, and can’t give the accuracy a human analyst can oﬀer. Automated tools face the challenges of heterogeneous protocol data which is often a mixture of text and binary, and it has diﬀerent data types and variable-length ﬁelds and this is the reason I have created this training, it is to help you understand these challenges and learn to recover protocol speciﬁcation.

This training is divided into two parts, in the ﬁrst part we will learn about Protocol Reverse Engineering principles. We will look at some of the common data formats and other protocol structures and with that understanding we will write a protocol dissector using Scapy framework for a target Desktop game Minetest (open source implementation of Minecraft). Minetest is online multiplayer game in which diﬀerent players can connect to the server and play with other players, there are also many public servers which you can connect and play. Once we have written the decoder we will sniﬀ the connection and look at the communication ﬂow between the client and the server which we will capture and re-analyze the traﬃc to improve the dissector further, using this newly improved dissector we will implement a custom game client/bot which will connect to the server and play as a Bot player.

In the second part, with a decent understanding of the Minetest Protocol we will move on to the oﬀensive side of the training and try to fuzz the game server to ﬁnd some security vulnerabilities, we will start with basic Fuzzer and try to do incremental improvement such that we have good code coverage. Leveraging their reverse-engineered understanding of the protocol, participants will employ Generational Fuzzing by defining the protocol specification in the Boofuzz fuzzing framework and subsequently fuzzing the application. The training will also explore Mutation Fuzzing as an alternative approach to identify potential crashes or vulnerabilities.

## Why should people attend your course?

* Hands-on Labs
* The joy of Reverse Engineer (looking under the hood)
* Getting familiar with Network Protocol Analysis
* Unlimited Email Support.
* What not to expect: Become a Protocol Reversing Ninja.

Use the knowledge gained in this training to start exploring some Open and Close Protocol to improve your understanding of this topic. That will help you to get a deeper understanding of some underlying issues more closely.

## Course Outline

1. Networking Basics
1. Capturing Network Traffic
    1. Passive analysis
        1. Network Sniffing
        1. Syscall hooking (strace)
    1. Active analysis
        1. Network Proxies
1. Protocol Reversing
    1. Protocol Structure
        1. Common data format
        1. Data Encoding
        1. Binary Protocol Structure
        1. Text Protocol Structure
    1. Protocol Flow
1. Protocol Dissector (targeting Minetest game)
    1. Scapy 101
    1. Implementing protocol dissector in scapy for Minetent game. This section will have Labs on
        1. Protocol decoding TLV format
        1. Packet decompression
        1. Packet Reassembly
1. Custom Client (Bot Player for Minetest Game)
    1. Brief Understanding of Application
    1. Authenticate the client
    1. Establish a valid session
    1. Some game hacks like making the player fly
    1. Create A Bot Army (if time permits)
1. Protocol Fuzzing (targeting Minetest game)
    1. What is fuzzing?
    1. Implement Mutation Fuzzer
    1. Implement Dumb Fuzzer
    1. Implement Generation Fuzzing (Protocol Aware Fuzzing)
    1. Createing Harness

## Tools of the Trade

Below are some of the tools that you will learn in this training that will make you Protocol Reversing experience more fun.

1. Protocol Reversing tools
1. Wireshark
1. Scapy
1. strace
1. scapy
1. Protocol Fuzzing Tool
1. Boofuzz (Sulley) fuzzing framework

## Your Instructor

<img src="/assets/images/2025/Photo-Munawwar_Hussain_Sheila.jpg" alt="Photo of Munawwar Hussain Shelia" style="float: left; width: 125px; margin-right: 15px;" />

**Munawwar Hussain Shelia** is currently working as a Vulnerability Researcher at Qualcomm. His primary role involves hunting bug and squashing them before product hits the market. He also develops tools to automate the process of bug detection. With a background Reverse engineeering and software development, he possesses a unique perspective on product design which enabling him to eﬀectively identify vulnerabilities. In 2019, he conducted the “Practical IoT Hacking” Training at Nullcon and other conferences. Additionally, he also delivered a talk at the diﬀerent conferences. His areas of expertise include Reverse Engineering, Binary Analysis, Malware Analysis, and Software Exploitation, topics on which he frequently shares insights through his blog, https://taintedbits.com. He has conducted training for various governmental and private organizations worldwide. Notably, he has discovered and reported vulnerabilities in IoT devices and published a paper on Android Malware.
