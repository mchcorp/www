---
layout: nosplash
permalink: /sca/
title: "Software Composition Analysis (SCA)"
excerpt: "Software Composition Analysis (SCA)"
last_modified_at: 2021-11-28T10:23:16-04:00
toc: true
---

Software Composition Analysis (SCA)

## What is Software Composition Analysis (SCA)? 

SCA is a method for managing and securing open-source software components within a codebase. It involves identifying and inventorying open-source components to understand the risks associated with their use, such as licensing issues, outdated versions, and potential security vulnerabilities.

SCA tools can automatically scan a software codebase and detect all open-source components, including direct and indirect dependencies. They match these components against known vulnerability databases, licensing databases, and version histories to provide a comprehensive risk profile for the open-source usage within a given application.

This process helps organizations to maintain the compliance, security, and quality of their software products. It is a crucial part of modern software development processes, especially in environments that heavily utilize open-source components

SCA allows organizations to:

Identify and track the use of open-source software within their code.

Understand the potential security, licensing, and maintenance risks associated with each component.

Take appropriate action to mitigate those risks, whether that's updating to a newer version, replacing a problematic component, or addressing a security vulnerability.

### How is Dynamic Application Security Testing (DAST) performed?

DAST is performed while the application is running, thus simulating a real-world attack scenario. Here's a generalized step-by-step process of how DAST is typically conducted:

Planning and Preparation: In this stage, you define the scope of the test, identify the areas of the application to be tested, and understand the functionalities of the application. This stage also involves setting up the DAST tools and environment.

Spidering/Crawling: Once the application is running, the DAST tool starts by 'crawling' or 'spidering' through the application. This process is similar to how search engine bots crawl websites. The tool follows links, maps out site structure, and analyzes different elements such as URLs, cookies, forms, and scripts present in the application.

Attack Simulation: After the application has been thoroughly mapped, the DAST tool starts to simulate attacks on the discovered entry points. It sends various malicious inputs or exploits to these points and observes the application's responses.

Analysis: The DAST tool analyzes the application's responses to the simulated attacks. If the application returns an error message, crashes, or behaves unusually in response to the malicious input, the tool flags the input as a potential vulnerability.

Reporting: Once the test is complete, the DAST tool generates a report detailing all the discovered vulnerabilities, along with information such as the location of the vulnerability, the potential impact, and suggested remediation steps.

Remediation: The final step involves taking action based on the report. This could include fixing the code, implementing security controls, and then retesting to verify that the vulnerabilities have been adequately addressed.

While DAST provides valuable insights into vulnerabilities that can be exploited at runtime, it's generally recommended to use it in conjunction with other testing methods (like SAST) to achieve a more comprehensive view of application security. Each method has its strengths and weaknesses, and a multi-faceted approach can provide the most robust protection.

### How is Software Composition Analysis (SCA) performed?

Inventory Creation: The first step in SCA involves scanning the software codebase and creating an inventory of all open-source components. This includes libraries and other third-party components, along with their respective versions. The inventory should also include dependencies since these may also bring in open-source components with their own risks.

Vulnerability Analysis: Once the inventory is complete, each component is checked against vulnerability databases like the National Vulnerability Database (NVD) or proprietary vulnerability databases maintained by SCA tool vendors. These databases contain lists of known security vulnerabilities along with the software versions they affect.

License Compliance Checking: SCA tools also analyze the license associated with each open-source component. This is critical to ensure compliance with the terms of use for each component. For example, some licenses may require attribution, while others may mandate that any derivative work also be open source.

Version Checking: It's important to know whether the components in use are up to date. Using outdated versions may expose the software to vulnerabilities that have been patched in later versions. It may also mean missing out on improvements or features.

Policy Enforcement: Organizations often have policies regarding the use of open-source software, such as which licenses are acceptable or what level of vulnerability risk is acceptable. SCA can enforce these policies by flagging violations for review.

Reporting and Remediation: After analysis, the SCA tool typically produces a report detailing all the findings. If potential issues are identified, the team can then decide on the appropriate remediation steps. This could include updating a component to a newer version, replacing it with an alternative, or potentially even rearchitecting the software if a critical issue is identified.

By utilizing SCA, organizations can better manage the risks associated with using open-source components, ensuring that they reap the benefits of open source while mitigating potential legal and security risks.

### Why MCH is the right service provider to select for your SCA analysis needs?

Here are some key considerations to keep in mind:

MCH provides excellent coverage in performing SCA analysis.  The tools we use have broad language and package manager support.  It can identify all open-source components, including transitive dependencies, used in your software regardless of the programming languages and package managers you use.

MCH has an extensive vulnerability database.  The tools we use provide a robust, frequently updated database of known vulnerabilities with data supplemented from public databases as well as our own research and other private sources of data

Our analysis results are delivered in detailed, actionable reports designed to help both developers and security teams understand and act on the SCA results.

Our pricing model is very affordable and provides excellent value for the money.

---
