---
layout: nosplash
permalink: /sast/
title: "Static Application Security Testing (SAST)"
excerpt: "Static Application Security Testing (SAST)"
last_modified_at: 2021-11-28T10:23:16-04:00
toc: true
---

Static Application Security Testing (SAST)

## What is Static Application Security Testing (SAST)? 

SAST is a type of security testing methodology that examines the source code of an application to identify potential security vulnerabilities. It's often referred to as "white box" testing because it looks at the internal structure of the application, rather than just its functionality.

SAST can identify security issues such as input validation errors, code vulnerabilities, insecure functionality, and other potential problems early in the software development lifecycle, often before the code is compiled and executed. This makes it a valuable tool in a "shift left" approach to software development, where potential issues are identified and remedied as early as possible.

The benefits of SAST include its ability to analyze an entire codebase quickly, its applicability to a wide range of programming languages, and its effectiveness at catching issues early when they're typically cheaper and easier to fix. However, because it doesn't analyze the application in a running state, it can't identify every potential vulnerability, especially those that arise from the way different components interact in a running application. For this reason, SAST is often used in conjunction with other types of security testing, like Dynamic Application Security Testing (DAST).

### How is Static Application Security Testing (SAST) performed?

Static Application Security Testing (SAST) is a white-box testing methodology that focuses on examining the application's source code to find potential security vulnerabilities. Here's a general outline of how SAST is usually performed:

- **Preparation** — The first step in SAST involves identifying the scope of the testing, such as which parts of the codebase to analyze. The source code is then prepared for analysis, which might involve building a version of the application that's compatible with the SAST tool.

- **Static Code Analysis** — The SAST tool scans the source code, examining it line by line. It uses predefined rules or patterns that correspond to known vulnerabilities, such as SQL injection or buffer overflow vulnerabilities. If it finds a piece of code that matches one of these patterns, it flags it as a potential vulnerability.

- **Data Flow Analysis** — Some SAST tools also perform data flow analysis, tracking the flow of data through the application to identify potential vulnerabilities related to the handling of sensitive data.

- **Results Interpretation** — After scanning, the SAST tool produces a report that lists the potential vulnerabilities it found, usually ranked by severity. These results need to be interpreted and validated, as there can be false positives (benign code flagged as vulnerable) and false negatives (actual vulnerabilities that weren't flagged).

- **Remediation** — Once the vulnerabilities have been identified and validated, the next step is remediation. This typically involves modifying the code to eliminate the vulnerability, then retesting to ensure the vulnerability has been properly addressed.

- **Integration into SDLC** — Ideally, SAST is integrated into the software development life cycle (SDLC).  This helps catch vulnerabilities early, before they make it into the production code.

One of the main advantages of SAST is its ability to catch vulnerabilities early in the development process, which can save time and resources compared to catching them later. However, it's worth noting that SAST can't catch every type of vulnerability, especially ones that only become apparent when the application is running. For that reason, it's often used in conjunction with dynamic application security testing (DAST) to provide a more comprehensive approach to application security.

### Why MCH is the right service provider to select for your SAST needs?

Choosing the right Static Application Security Testing (SAST) service provider is an important decision that can significantly impact the security posture of an organization's applications. Here are some key considerations when making your selection:

- **Compatibility and Scope** — The SAST tool employed by your service provider needs to support the programming languages and frameworks your organization uses.

- **Accuracy** — The tool employed by your service provider should have a high accuracy rate in identifying potential vulnerabilities.  More importantly, your service provider needs experts to review the finding indications and determine which finding indications are confirmable and which are false positives.  Time and again it’s been proven this cannot be fully automated. Delivering false positives to development staff can waste valuable time, while false negatives can leave vulnerabilities undetected.

- **Reporting and Remediation Guidance** — The tool should generate clear, understandable reports, providing actionable insights and guidance on how to remediate identified vulnerabilities.

- **Reputation and Reviews** — Consider the provider's reputation in the industry. Look for independent reviews and case studies. Ask for references if possible.

- **Pricing** — Evaluate the pricing model and make sure it aligns with your budget. Consider both immediate and long-term costs.  As MCH is a subcontractor to a number of major testing houses, our pricing is lower than most of our competition.  We provide the same (or typically higher quality) results as we are staffed by proven AppSec experts with a wealth of experience that other larger firms to turn to for their highest profile projects.

---
