---
layout: workshop
title: Finding and exploiting basic buffer overflows
details: true
track: 1
accepted: true
timeslot:
  start: 2021-06-20T10:00:00+02:00
  duration: 240
links:
  wstickets_uri: https://pretix.eu/BSidesMEsh21/Workshops-CTF/
speakers:
  - name: Christian Gross
    handle: gravitons13
    bio:  |
      - 3.5 years of working experience in Infosec
      - Infosec as a hobby / past-time since teenage years
      - OSCP/OSCE holder
  - name: Sarah Mader
    handle: 
    bio:  |
      - Freshly graduated Master student with 1.5 years of working experience in Infosec
      - Main focus on IoT / Hardware hacking, especially Bluetooth technology
      - Binary Exploitation / Reverse Engineering Hobbyist
---

Binary exploitation is one of the oldest IT security topics but it is still very relevant today.
When the *Shadowbrokers* released a collection of weaponized NSA binary exploits the world was at danger.
These exploits were used by criminals to write the ransomware WannaCry which infected hundreds of thousands of computers world-wide.
The exploit can only be understood by deep-diving into binary exploitation.
However, understanding the concepts behind buffer overflows and many other sophisticated types of vulnerabilities is very difficult.
A lot of prerequisite knowledge is needed about specific computer architectures and assembly language.
Web application security for instance is equally as complex but much more approachable because the prerequisite knowledge is required only in smaller chunks.
With this workshop I want to make it easy for people to jump into the topic of binary exploitation and just begin hacking.

The beginning of the workshop covers what types of vulnerabilities exist and prepares the participants for the main part of the course.
The main part is a hands-on experience featuring finding vulnerabilities by fuzzing with boofuzz and developing a fully working working exploit in Immunity Debugger to achieve remote code execution through a software called vulnserver.
Vulnserver is an open-source and intentionally left vulnerable software to practice exploiting different vulnerabilities.

After the course the participants will have a basic understanding about binary exploitation, how to find vulnerabilities and how to write their own exploits.