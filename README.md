
# Train Ticket：A Benchmark Microservice System
# <img src="./image/logo.png">


The project is a train ticket booking system based on microservice architecture which contains 41 microservices. The programming languages and frameworks it used are as below.
- Java - Spring Boot, Spring Cloud
- Node.js - Express
- Python - Django
- Go - Webgo
- DB - Mongo、MySQL

You can get more details at [Wiki Pages](https://github.com/FudanSELab/train-ticket/wiki).

## Service Architecture Graph
![architecture](./image/2.png)

Include a concise summary of the project and its goal.
Briefly mention the methodology used for vulnerability analysis (manual testing, automated tools).
Provide a high-level overview of the discovered vulnerabilities, their severity, and impact.
Include links to relevant references, tools, or resources used in the analysis.
Add badges for used technologies or frameworks (optional).
Additional points:

Create separate READMEs for each project you have.
Include a license file if applicable.
Consider adding screenshots or visuals for better understanding (optional).
Here's a starting point for your README based on the report you provided:

# FudanSELab Train Ticket Vulnerability Analysis

This project analyzed the FudanSELab train ticket application for security vulnerabilities. It identified two key vulnerabilities:

Server-Side Code Injection (OWASP A3): Allows attackers to execute arbitrary code on the server, leading to data theft, system compromise, and other consequences.
Client-Side Code Injection (OWASP A4): Enables attackers to inject malicious code into the client-side JavaScript, potentially leading to Cross-Site Scripting (XSS) attacks and information theft.
See the full report for detailed findings, impact analysis, and recommendations for mitigation: [link to report].

Technologies: PHP, JavaScript, MySQLi

Credits: Yuval Sigura

License: MIT
