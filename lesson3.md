# Secure Software Design Lessons

---

## Lesson 1

Take a moment to think about what you learned in this lesson.  

- It's crucial to identify the importance, relevance, and cost of building security into your software.
- SDLC stands for the software design life cycle.
- SDL stands for security development life cycle.
- Software security entails building security into the software through an SDL in an SDLC.
- The three core elements of security are confidentiality, integrity, and availability.
- Threat modeling and attack surface validation throughout the SDL will alleviate security vulnerabilities.
- Integrating and evaluating software and hardware used by your organization will maximize your organization's software and security.
- There are eight major phases of the SDLC: planning, requirements, design, implementation, testing, deployment, maintenance, and end of life.

### Key Terms

- **hardware**: the physical components of a computer or electronic system
- **deployment phase**: during this phase of the SDLC, security is pushed out
- **design phase**: during this phase of the SDLC, requirements are prepared for the technical design
- **end of life phase**: during this phase of the SDLC, the proper steps for removing software completely are considered 
- **implementation phase**: during this phase of the SDLC, the resources involved in the application from a known resource are determined
- **maintenance phase**: during this phase of the SDLC, ongoing security monitoring is implemented
- **planning phase**: during this phase of the SDLC, a vision and next steps are created
- **requirement phase**: during this phase of the SDLC, necessary software requirements are determined 
- **secure code**: a principle design in coding that refers to code security best practices, safeguards, and protection against vulnerabilities
- **security development life cycle (SDL)**: a process that standardizes security best practices
- **software**: the program and operating systems used by a computer
- **software development life cycle (SDLC)**: a structured process that enables the production of software
- **testing phase**: during this phase of the SDLC, software is tested to verify its functions through a known environment
- **threat modeling**: a structured process to protect against vulnerabilities

---

## Lesson 2

- implementing an SDL program ensures that security is built into a software design rather than an afterthought.
- Some popular SDL models are BSIMM SSDL Touchpoints, the OWASP Code Review Guide, the Cisco Secure Development Life Cycle (Cisco SDL), and Microsoft's Trustworthy Computing Security Development Life Cycle. 
- Building Security In Maturing Model (BSIMM) studies real-world software security initiatives. It allows you to determine where your software security stands and how to develop it over time.
- There are 12 best BSIMM practices.
- The OWASP Software Assurance Maturity Model (SAMM) is a flexible and prescriptive framework for building security into software development organizations.
- The National Institute of Standards and Technology (NIST) provides research, information, and tools for government and corporate information security.
- The US Department of Homeland Security has an established Software Assurance Program.
- Common Computer Vulnerabilities and Exposures (CVE) is a list of information that aims to provide common names for publicly known security vulnerabilities.
- You must map whatever form of SDL you use to your current SDLC.
- Security metrics allow for corporations to make decisions regarding risk management requirements and security budgets and to show customers proof of security.
- Application security is the process of developing, adding, and testing security features within applications.
- Application security aims to prevent security vulnerabilities against threats.

### Key Terms

- **application security**: developing, adding, and testing security features to prevent vulnerabilities within applications
- **Building Security In Maturing Model (BSIMM)**: a study of real-world software security that allows you to develop your software security over time
- **dynamic analysis**: the analysis of computer software that is performed when executing programs on a real or virtual processor in real time
- **fuzz testing**: automated or semi-automated testing that provides invalid, unexpected, or random data to the computer software program
- **National Institute of Standards and Technology (NIST)**: provides research, information, and tools for government and corporate information security
- **measurement model**: a set of data security methods that developers take to protect against vulnerabilities
- **metric model**: allows an organization to determine the effectiveness of its security controls
- **Open Web Application Security Project (OWASP)**: a flexible and prospective framework to build security into your software development organization
- **static analysis**: the analysis of computer software that is performed without executing programs

---

## Lesson 3

Take a moment to think about what you learned in this lesson.  

- The Waterfall approach divides the process of software development into separate phases. The outcome of one phase acts as the input for the next phase.
- An advantage of the Waterfall method is splitting project deliveries into different stages, making it easier for an organization to control the development process.
- A disadvantage of the Waterfall method is that it does not allow time for reflection or revision to a design.
- A V-model is not designed to be linear, but instead, the stage is turned back upward after the coding phase is complete, creating the V shape.
- The Agile methodology mixes traditional and new software development practices.
- Agile software development uses collaboration between self-organizing and cross-functional teams.
- Agile has four core values and 12 principles that can be followed.
- Agile framework allows for customer satisfaction through rapid, continuous delivery of useful software.
- A disadvantage of Agile is that it is difficult to assess the effort required at the beginning of the SDL.
- Scrum framework allows for a development team to work flexibly and holistically to reach a common goal.
- Extreme programming intends to improve software quality and responsiveness.
- Extreme programming is a type of Agile software development.
- Consider your software development projects and determine which approach is most suitable for you.

### Key Terms

- **Agile methodology**: mixes traditional and new software development practices
- **extreme programming (XP)**: a software development methodology that is intended to improve software quality and responsiveness
- **Scrum**: flexible, holistic product development strategy where a development team works as a unit to reach a common goal
- **V-model**: a variation of the waterfall model, where the stage is turned back upwards after the coding phase
- **Waterfall methodology**: a sequential, step-by-step process for requirements

---

In this section, you discovered the importance of software security. You dove deep into the software development life cycle (SDLC) as well as the security development life cycle (SDL) and learned what software security and application security are, along with their differences. Your readings looked at the underlying challenges in creating secure software as they exist in processes, talent, and technology. You were also introduced to different maturity models. Now, you can recognize the industry maturity models for measuring software security programs and metrics. Finally, as you discovered SDL best practices and tools, you learned how to map SDL and SDLC.

The later parts of this section covered different secure software development approaches. You learned more about Waterfall and Agile, compared the two methods, and examined the pros and cons of each. This will help you to make informed decisions about which method is best to use when developing your software security.

---

## Lesson 4

Take a moment to think about what you learned in this lesson.  

- The Security Assessment (A1) phase is the first phase of the security development life cycle.
- During the Security Assessment (A1) phase, an initial project outline for security milestones is developed and integrated into the development project schedule. 
- During the Security Assessment (A1) phase, all key stakeholders should discuss, identify, and have a common understanding of the security and privacy implications, considerations, and requirements.
- The software security team should be included in the software development life cycles (SDLCs) kick-off meetings to ensure that security is a key element of the SDLC and built into the process. 
- A privacy impact assessment should include the summary of the legislation, required process steps, technologies and techniques, and any additional resources.
- Creating success criteria for any SDL phase makes it more effective and, in postmortem, helps identify what worked and what didn't. 
- Creating a key set of deliverables for each SDL phase allows for all required activities to have tangible documented outcomes. 
- In the SDL model, it is helpful to outline metrics that should be measured in each and every phase. 
- The three areas of focus in secure software requirements are gathering the software requirements, data classification, and managing data protection requirements. 
- The purpose of gathering the software requirements before a project kick-off is to avoid common project failures by identifying requirements at the beginning of a project.
- When identifying functional and non-functional requirements, consider the current organization as well as future business needs. 
- Operational requirements refer to how the system should function based on the environment in which the system will operate. 
- The three areas of compliance requirements are legal, financial, and industry standards.

### Key Terms

- **functional requirements**: requirements that describe what the system will do and its core purpose
- **non-functional requirements**: requirements that describe any constraints or restrictions on a design but do not impact the core purpose of the system
- **privacy impact assessment**: a process that evaluates issues and privacy impact rating in relation to the privacy of personally identifiable information in the software
- **product risk profile**: helps to determine the actual cost of the product from different perspectives
- **requirement traceability matrix**: a table that lists all of the security requirements 
- **Security Assessment (A1) phase**: the first phase of the security development life cycle in which the project team identifies the product risks and creates a project outline for security milestones
- **threat profile**: the environment in which the product will operate and potential threats in that environment

---

## Lesson 5

Take a moment to think about what you learned in this lesson.  

- The second phase of the security development life cycle involves bringing security considerations into the software development life cycle. 
- The software security policy defines what needs to be protected and how it will be protected. 
- Collaboration among the privacy function, the centralized group, or outside legal counsel during software security design represents many organizations' best practice. 
- Threat modeling is a process to pinpoint security threats and potential vulnerabilities that will help prioritize remediation.
- Threat modeling proactively prepares an organization for potential threats rather than reacting after threats are discovered. 
- Consider the business or organization to help determine the best approach for threat modeling.
- The following five steps of threat modeling will help an organization better understand how to best protect its assets: identify security objectives, survey the application, decompose it, identify threats, and identify vulnerabilities. 
- Data flow diagrams provide a visual representation of a process flow.
- Threats can be categorized by type: spoofing, tampering, repudiation, information disclosure, denial of service, and elevation of privilege, which make up the acronym STRIDE.
- PASTA methodology of threat modeling stands for the process of attack simulation and threat analysis. 
- After identifying threats, it is important to consider the design and implementation aspects of your software application to rank threats and vulnerabilities to your organization.
- Rank the organization's threats based on their probability and damage potential. 
- The DREAD model is one of the most popular risk models. The DREAD model consists of damage potential, reproducibility, exploitability, affected users, and discoverability. 
- The Web Application Security Frame (aka Application Security Frame) uses categories to organize common security vulnerabilities with a focus on web software applications. 
- Trike is a framework for security auditing from a risk management perspective.

### Key Terms

- **application-centric threat modeling**: threat models that start with visualizing the application you are building
- **asset-centric threat modeling**: threat models focused around senior management and protecting the assets of an organization
- **application decomposition**: determining the fundamental functions of an app
- **Architecture (A2) phase**: the second phase of the security development life cycle that examines security from perspective of business risks
- **data flow diagrams**: a visual representation of the threat flow
- **denial of service**: denying access to valid users
- **elevation of privilege**: privileged access to resources for gaining unauthorized access to information
- **information disclosure**: read a file that one was not granted access too
- **PASTA**: the process for attack simulation and threat analysis that gives a software security team a repeatable framework for identifying threats
- **repudiation**: performing illegal operations in a system that lacks the ability to trace the prohibited operations
- **risk model**: assess vulnerabilities during the software development process
- **software security policy**: defines what needs to be protected and how it will be protected
- **spoofing**: illegally accessing and using another user's credentials
- **tampering**: maliciously changing or modifying persistent data
- **third party codes**: reusable software developed externally from the organization's platforms
- **threat modeling**: a process to pinpoint security threats and potential vulnerabilities that will help prioritize remediation
- **threat source**: the entity carrying out the attack
- **threat vector**: the path an attacker can take to exploit a vulnerability
- **Trike**: a unified conceptual framework for security auditing 
- **vulnerability**: a weakness that can be exploited

Section 2 introduced the first two phases of the Security Development Life Cycle (SDL). The security assessment is where the project team identifies the product risk profile and what SDL activities are needed. The initial project outline for security milestones and controls is developed and integrated into the overall project schedule to allow proper planning as changes occur. The Architecture phase defines business requirements in terms of confidentiality, integrity, and availability and also identifies privacy controls that must be implemented to prevent leaking personally identifiable information (PII). Security teams perform threat modeling in the Architecture phase by creating data flow diagrams of business processes and identifying threats to each element of the product design.

---
## Lesson 6

Take a moment to think about what you learned in this lesson.  

- During the A3 phase, any policy that exists outside of the SDL policy is reviewed.
- Both the software security group and the centralized information security group must collaborate on all policies and guidelines.
- The purpose of testing activities is to validate the security of software before making the product available.
- The goal is to build security in, which is less costly than correcting problems discovered after the software has been deployed.
- The test environment should mimic the execution environment as closely as possible.
- Software security testing techniques are categorized by white box, gray box, or black box testing.
- Developers test their systems to ensure that their code is working properly; this is known as alpha testing.
- External testing, known as beta testing, allows you to check usability and vulnerabilities in a system.
- Security test cases allow a software developer to determine security issues at the lowest level.
- The process of scanning involves identifying deficiencies anywhere around the system.
- Security testing is not static; it is ongoing.
- Applications need to be tested not only in the lab or development area but also in their true operational environment. 

### Key Terms

- **alpha level testing**: testing done by the developers themselves
- **beta level testing**: testing done by those not familiar with the actual development of the system
- **black box testing**: tests from an external perspective with no prior knowledge of the software
- **Design and Development (A3) phase**: the third phase of the security development life cycle, in which you analyze and test software to determine security and privacy issues as you make informed decisions moving forward with your software
- **external resources**: resources hired on a temporary basis to come into a project, test the application, and report findings
- **functional testing scripts**: step-by-step instructions for a specific scenario or situation
- **gray box testing**: analyzes the source code for the software to help design the test cases
- **internal resources**: resources from the company's organization
- **secure testing scripts**: scripts created specifically for the application being tested
- **scripts**: detailed, logical steps of instructions to tell a person or tool what to do during the testing
- **system test**: test the system and its interaction with other systems
- **white box testing**: tests from an internal perspective with full knowledge of the software
- **vulnerability assessments**: examining a product to identify security deficiencies

---

## Lesson 7

Take a moment to think about what you learned in this lesson.  

- During the A4 phase, any policy that exists outside the domain of the SDL policy is reviewed.
- Quality assurance testing occurs throughout the entire SDLC process.
- The three specific test type categories are benchmarks, scheduled tests, and exploratory tests.
- Code review finds and fixes a large number of security issues before the code is tested or shipped.
- The four basic techniques for code review are automated scanning, manual penetration testing, static analysis, and manual code review.
- AppSec describes finding, fixing, and preventing vulnerabilities at the application level.
- AppSec is difficult to scale for large organizations.
- The goal of code review is to catch bugs early on to decrease the cost of fixing them.
- Proxy scripts are effectively used to communicate a web security bug or web security control.
- Active and passive scanner scripts identify common vulnerabilities that are specific to your application.
- SonarQube gives developers the ability to continuously inspect the quality of code they produce.

### Key Terms

- **abstract syntax tree (AST)**: the basis for software metrics and issues to be generated at a later stage
- **active scanner**: modifies the hypertext transfer protocol secure (HTTPS) inputs and analyzes the response to identify vulnerabilities
- **AppSec**: the process of finding, fixing, and preventing security vulnerabilities at the application level
- **benchmarks**: tests used to compare estimates to actual results
- **code review**: a process done to identify security vulnerabilities during software development
- **control flow analysis**: the mechanism used to step through logical conditions in the code
- **data flow analysis**: the mechanism used to trace data from the points of input to the points of output
- **Design and Development (A4) phase**: the fourth phase of the security development life cycle, in which you will build onto the proper process of security testing and continue to analyze necessities at the security level
- **documentation**: details and guides that are necessary to support the ongoing use of the software
- **dynamic analysis**: application security testing to identify vulnerabilities within a product application
- **exploratory tests**: done by the development tester to continually assess the quality of his or her work
- **Open Source Security Testing Methodology Manual**: a manual that provides templates and standards used when developing a test strategy
- **OWASP Zed Attack Proxy**: an open-source security tool used widely by software security developers
- **passive scanner**: silently analyzes all the hypertext transfer protocol (HTTP) requests and responses passing through the web application security tool
- **pull request**: a request to merge your code into another branch
- **scheduled tests**: mandatory requirements testing to validate the security of the software and associated system(s)
- **SonarQube**: open-source platform for static code analysis that can detect bugs, code smells, vulnerabilities, and hotspots in over 25 programming languages.
- **spider**: identifies inputs and supplies those to the scanning components of the security tool
- **static analysis**: analysis of computer software that is performed without actually executing programs
- **Zed Attack Proxy (ZAP)**: free, open-source penetration-testing tool

---

## Lesson 8

Take a moment to think about what you learned in this lesson.  

- The Ship (A5) phase of the SDLC occurs when the security team performs its final analysis and security review on the applications or software. 
- Policy compliance analysis verifies the product meets quality standards before the release of an application or software. 
- Vulnerability scanning tools attempt to identify weakness in the applications.
- Penetration testing simulates the actions of a hacker to attempt to identify vulnerabilities within the software.
- The four phases of penetration testing are: assess, identify, evaluate and plan, and deploy.
- Active and passive analysis techniques are both useful during vulnerability testing.
- Creating a networking laboratory allows you to test within a controlled environment without written authorization and permissions.
- NMap is a popular network scanning tool.
- There are many techniques that can be used to discover vulnerabilities; it is important to consider which technique will be best for your software or application.

### Key Terms

- **authenticated scans**: scans that require software to log onto a system to scan it
- **external scans**: scans that target security issues that are found outside the firewall
- **internal scans**: scans to identify security issues that a malicious attacker could exploit from inside the network
- **intrusive target search**: scans to exploit a vulnerability when it is identified
- **Nmap**: a tool used for network scanning and security auditing
- **open-source software license compliance**: regulations regarding the software licensing of in-house products
- **open-source software security**: identifying software security within in-house developed software
- **penetration testing**: an authorized attack of an application to determine its weaknesses
- **range**: a networking laboratory created to conduct vulnerability analysis testing
- **Ship (A5) phase**: the fifth phase of the security development lifecycle that verifies that the product complies with security policies
- **SQL injection**: a code injection that might destroy your software
- **target machine**: a virtual space to practice identifying attack surfaces of the machine
- **virtualization**: technology used to create software services 
- **vulnerability scan**: explore application and databases to attempt to identify weaknesses
- **vulnerability sites**: websites with information on the latest known vulnerabilities

---

## Lesson 9

Take a moment to think about what you learned in this lesson.  

- Having software security experts report to the engineering organization allows for a stronger relationship during the software security development process. 
- Quality security is built throughout the entire engineering process, not in just one phase of the development life cycle.
- Not every company will be able to include all PRSAs, so consider which has the highest value to your organization and how to optimize the tools you do have access to. 
- CVSS is a model that is used to assess the severity of a vulnerability. 
- Post-release privacy issues may need additional development, quality assurance, and/or security resources.
- Third-party reviews may be necessary when completing a post-release review.
- During a company's merger or acquisition, software security may go under architectural review to identify any changes that will need to take place once the merger or acquisition is complete.
- Requirements for post-release certifications should be included in security and privacy requirements before deployment.

### Key Terms

- **Common Vulnerability Scoring System (CVSS)**: a model used to assess the severity of a vulnerability
- **legacy code**: old code that is no longer supported
- **merger and acquisition (M&A)**: when companies consolidate
- **Product Security Incident Response Team (PSIRT)**: the team that receives, investigates, and reports security vulnerabilities
- **Post-Release Support phase**: the phase of the SDLC in which organizations prepare for vulnerabilities after the product has been released
- **Post-Release PSIRT Response**: responds to software product security incidents that involve the external discovery of post-release software vulnerabilities
- **Software Security Champion (SSC)**: an expert on promoting security awareness, best practices, and simplifying software security 
- **Software Security Evangelist (SSE)**: an expert to promote awareness of products to the wider software community

---

## Lesson 10

Take a moment to think about what you learned in this lesson.  

- Your software is most likely to be deployed in Agile, DevOps, Digital Enterprise, or a combination of those environments.
- Agile development is designed to deliver value faster. 
- DevOps teams work together for ongoing operations, enhancements, defect removal, and optimization of resources.
- Cloud technology has created a rethinking on how applications are built, deployed, and used. 
- Digital enterprises use technology to assist in enabling and improving business activities. 
- Moving to public cloud services has increased security challenges.
- OpenSAMM business functions include governance, construction, verification, and deployment.
- Building Security in Maturity Model (BSIMM) is a study of existing software security initiatives used to gather data from larger software development.
- The four types of BSIMM categories are governance, intelligence, software security development life cycle touchpoints, and deployment. 
- Companies can use BSIMM documents to conduct their own assessments. 
- Threats can be classified using the STRIDE acronym: spoofing, tampering, repudiation, information disclosed, denial of service, and elevation of privilege.

### Key Terms

- **code review (CR)**: a practice of verification involving review of an organization's secure code to identify vulnerabilities
- **construction**: a function of OpenSAMM centered around how organizations define goals and create software within development projects
- **deployment**: a function of OpenSAMM centered around how an organization releases software
- **design review (DR)**: a practice of verification involving inspecting artifacts that were created from the design process
- **digital enterprise**: technology used to enable and improve business activities
- **education and guidance (EG)**: a practice of governance involving increasing security knowledge among software developers
- **environment hardening (EH)**: a practice of deployment involving implementing controls for the operating environment of an organization's software
- **governance**: a function of OpenSAMM centered on how organizations manage overall software development activities
- **Open Software Assurance Maturity Model (OpenSAMM)**: an open framework to help organizations implement software security tailored to the organization's specific risks
- **Operational Enablement (OE)**: a practice of deployment involving identifying and capturing security-relevant information
- **policy and compliance (PC)**: a practice of governance involving setting up security and compliance control 
- **secure architecture (SA)**: a practice of construction involving activities to prompt secure-by-default designs during the design process
- **security requirements (SR)**: a practice of construction involving the promoting of inclusion security requirements during software development
- **security testing (ST)**: a practice of verification involving testing the organization's software in its environment 
- **strategy and metrics (SM)**: a practice of governance involving the strategies regarding software assurance and processes to collect metrics on an organization's security
- **threat assessment (TA)**: a practice of construction involving identifying and characterizing potential threats
- **verification**: a function of OpenSAMM centered around how an organization checks and tests artifacts produced through software development
- **vulnerability management (VM)**: a practice of deployment involving establishing processes for managing internal and external vulnerability reports

---
