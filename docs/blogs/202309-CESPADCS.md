---
draft: false
date: 2023-09-02
readtime: 5
categories:
  - Exam
  - Certification
  - RedTeaming
tags:
  - Exam
  - Certification
  - RedTeaming
  - ADCS
---

# 202309 - Altered Security CESP-ADCS Review

---

## Course Overview

With knowledge of the previous red team courses from [Nikhil Mittal](https://in.linkedin.com/in/mittalnikhil), also the author of the famous offensive PowerShell tool [Nishang](https://github.com/samratashok/nishang), it feels much easier to understand how Active Directory really works and how it is commonly misconfigured, allowing attackers to abuse and dorminate a forest.

[Active Directory Certificate Services (ADCS)](https://learn.microsoft.com/en-us/windows-server/identity/ad-cs/active-directory-certificate-services-overview) is Microsoft’s Public Key Infrastructure (PKI) for typical Windows environments. It would also be interesting to understand more from the red team perspective to assist in the defensive measures like writing detection use cases and spotting misconfigurations. Upon the release of the new [ADCS course](https://www.alteredsecurity.com/adcs), I joined it as soon as it became available!

<br/>

---

## Course Review

Like in the previous courses, you are given the VPN access and Web access to the lab environment, and also the course slides, videos etc.

The course uses a step-by-step approach to walk through concepts such as red teaming basics (e.g., AV Bypass, PowerShell Logging bypass, etc.), the workings of AD CS, different attack paths in AD CS environments, and tools for AD CS attacks, etc. You may refer to the [Altered Security ADCS Course Page](https://www.alteredsecurity.com/adcs) to learn more about the course itself.

As a student who does not have much experience in configuring, defending and attacking ADCS, this course provides much knowledge, in additional to the basic AD attack surfaces learnt in the previous CRTP, CRTE and CRTM courses. For someone who has no experience and knowledge in AD attacks, definitely check out the [CRTP course](https://www.alteredsecurity.com/adlab) to learn the fundamentals first.

My approach to studying the course involves thorough review of the course slides, accompanied by note-taking in Markdown format for easy reference during practical work and lab building. Unless faced with substantial knowledge gaps, I tend to skip the course videos due to their similarity to the course slides.

I highly value encountering challenges while working on the labs. The lab manual, which offers step-by-step instructions for both Windows and Linux environments, enhances flexibility and provides valuable real-life experience for engagements in the field.

Each lab requires submission of flags on the learning portal to ensure comprehensive understanding and adherence to the course materials.

Personally, I have subscribed to the lab for a 30-day duration, which has proven more than sufficient to complete the materials at hand.

I believe most of the materials are closely relevant to the [SpecterOps's Certified Pre-Owned Whitepaper](https://specterops.io/wp-content/uploads/sites/3/2022/06/Certified_Pre-Owned.pdf). To gain a comprehensive understanding of the content, I highly recommend referring to this whitepaper as a valuable resource.

<br/>

---

## Examination

In regards to the exam, it allocats a 24-hour timeframe to operate within the exam lab environment, followed by an additional 48 hours to submit the exam report.

During the exam, the focus lies on leveraging the knowledge acquired throughout the course, without the need for any additional resources. The objective entails identifying the attack path to compromise a single AD domain consisting of 5 machines, including the foothold machine. As long as the course material is thoroughly understood and followed, success in the exam should be achievable without significant obstacles.

TIPS: Again - enumeration is always the main key to success. Make sure you understand how the vulnerabilities are found and what the tools outputs mean in the lab environment; or otherwise it would be easy to get lost!

At the end I was able to finish and submit the report in 8 hours. After submitting the report around 5 days, I am certified!

![](images/2023-09-02-22-22-59.png)

Thanks for reading this. Have been having some thought on building an ADCS lab and build some detection use cases in the future. Stay tuned!

<br/>

---