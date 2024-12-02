This page outlines and describes various topics a cybersecurity candidate should know when applying for any entry-level cybersecurity job.   

Obtaining one or more of the recommended certifications may provide a base level of knowledge, but there are many other things that you should research and become familiar with. There may be more than [1,000,000 available cyber jobs available today](https://www.forbes.com/sites/jackkelly/2024/08/16/nearly-4-million-cybersecurity-jobs-are-vacant-heres-why-you-should-consider-breaking-into-this-sector/), but only a small portion of those are entry-level positions, and there are thousands of other entry-level candidates trying to break into the cybersecurity industry along with you.   

To separate yourself from that large group of candidates and stand out, you must have a broader, more refined level of knowledge in the area you are trying to apply.  This commonly requires a bit of self-studying and research. Build a home lab and practice various security concepts.  You may not be able to play with enterprise-class tools yet, but if you learn the underlying principles of how they work, then the tool's name won't matter, and you can easily change tools fairly quickly because you understand the concepts.   

For example, you will only have access to commercial vulnerability scanning tools once you get a job in that role. However, by learning the concepts at home through free tools like Nessus or OpenVAS, you will learn most of the core principles used by those enterprise tools. You only need to learn their GUI or way of doing it. **To be competitive, you MUST do more than study the general cybersecurity curriculum and take a certification exam.**

### Baseline Security Knowledge  
This section applies to knowledge you should know and feel comfortable with for almost all cybersecurity roles or positions.   

+ **Collaboration Tools** - You should be very familiar and comfortable with the use of common enterprise collaboration tools such as Google or Microsoft suite of tools. OneDrive, SharePoint, Teams, cloud sharing, etc., are commonly used in organizations and within cybersecurity.
+ **Networking Concepts** - You should feel very comfortable with network concepts, including understanding public vs. private IP spacing, subnetting, gateways, CIDR notation, etc.  You should be able to easily explain how the Internet at your house works, each step or device it goes through, how address translation works, the different network layers, how DHCP works, how DNS works, how HTTP works, etc.  You should know the top 10 most common network ports a typical person or business uses.
+ **Social Engineering Concepts** - Since social engineering is the biggest threat to organizations, you should understand the common social engineering tactics used by threat actors and how they work at a high level.
+ **Industry Security Frameworks** - At a high level, you should be familiar with the various security frameworks commonly used in organizations. You don't need to memorize each section but should be familiar with them.
+ **Virtualization** - You should be comfortable installing, configuring, and using a type II hypervisor to virtualize various operating systems. Virtualization is a very common technique for testing and learning various topics.
+ **Linux Operating System** - You don't need to be an expert, but you should be familiar with installing, configuring, and using a Linux operating system. Due to their open-source and free-licensing nature, Linux operating systems are very common in enterprise environments and commonly used by security team members for virtualization and testing. Knowledge of common command-line utilities, such as grep, sed, awk, sort, wc, and cut.
+ **Encryption** - Since data privacy and protection are core tenets of cybersecurity, you should understand the basic types (symmetric and asymmetric) and uses of encryption.
+ **Active Directory / Entry ID** - You should understand the concept of Active Directory (on-prem) and/or Entra ID (Azure) for managing an organization's identities. Since almost all organizations use a central identity management platform (Active Directory and Entra ID are the most common), knowing how they work is important.
+ **Cloud Services** - Firm understanding of cloud service types (IaaS, PaaS, SaaS). Familiar with setting up and managing IaaS.

#### Optional, But Strongly Recommended
+ **Python and/or PowerShell programming** - A basic level of knowledge using Python or PowerShell from the command line and through scripts to query, extract, manipulate, and generate data/information. For example, using a PowerShell cmdlet is very common for a security operations analyst who may need to query or disable an account.
+ **BASH Shell scripting** - The ability to read/write bash shell scripts is valuable.  

### Security Operations (blue team)
+ **SIEM & Logging concepts** - You should know how SIEMs work. Logging and SIEMs are fundamental to organizations' monitoring and responding to abnormal activity. If you work in a Security Operations Center (SOC), you will be spending 90% of your time in a SIEM,
+ **Event Logging** - You should know the common log events in Windows and Linux systems. For example, what are events 4624, 4625, and 4634?  Where are these logs on the endpoints before being sent to the SIEM? What are interactive logins vs. network logins?  What is the difference between endpoint logs and AD/Entra ID logs?
+ **Endpoint Protection Platforms (EPP)** - You should be familiar with common EPP tools and who are the stronger ones. It is unlikely you can get access to common commercial EPP tools, but understanding their capabilities and what you can do to a single (or multiple endpoints) during a response is important. 
+ **Identity Management** - You should be familiar with the concepts of researching and disabling accounts via active directory / Entra ID.

### Incident Response
+ **Endpoint Knowledge** - You should have a firm understanding of the different operating systems used on our endpoints, servers, network devices, etc. What is normal behavior and processes vs. what is unusual? A firm understanding of account management (local and directory)
 + **Endpoint Protection Platforms (EPP)** - Excellent knowledge of how EPPs work and how they can be used to mitigate various threats.
 + **Network Concepts** - Expert-level understanding of networking concepts. 
 + **Programming / Scripting / Command line tools** - Solid knowledge of scripting techniques and various command line tools to parse, search & format data.

### Vulnerability Management
+ **Commercial Vulnerability Scanners** - You should know the three most common vulnerability scanners. For the ones that provide a free/trial version, you should download, install, and use it to scan your home network to see how it performs and looks. 
+ **Scanner Concepts**—You should understand all the common options and their meanings found in a network vulnerability scanner. Understand the pros/cons of network scanners vs. host-based assessment. How credential-based scans work.   The difference between patch management and vulnerability management. Why are vulnerability metadata such as first and last-seen dates important, and how are they used? 
+ **CVSS & KEV** - A full understanding of CVSS and KEV, and how an organization would commonly use these to prioritize vulnerabilities.
+ **Threat Intelligence** - The role of threat intelligence and how exploitability plays an important role in prioritization.
+ **Reporting & Metrics** - What metrics and reporting are commonly used to assess the effectiveness of vulnerability detection and remediation? What metrics and reporting are important for the effective remediation of vulnerabilities? 

### Offensive Security / Penetration Testing (red team)
 + **Network Concepts** - Expert-level understanding of networking concepts. Full understanding of the OSI model and the services & protocols at each layer. 
 + **Web Application Security** Solid understanding of web application security concepts, including all concepts in the OWASP top 10. Solid familiarity with using common pen testing tools, such as Burp, Nikto, Metasploit, etc. Most good pen testers rely less on automated tools and more on manipulating how an application works and how to send data to the application. 
 + **Social Engineering**—Pen testing may include various controls, such as phishing employees, assessing wireless networks, using removable storage devices, and lock picking. 

### Security Awareness
+ **Security Training Platforms** - Familiarity with security training platforms or LMS systems to deliver company-wide security training.
+ **Social Engineering Concepts**  - Expert-level knowledge of social engineering techniques.
+ **Writing & Speaking Skills** - Ability to publish articles, blog posts, and awareness messages for all employees.  Ability to deliver presentations in-person or virtually.
+ **Phishing Simulation Testing** - Solid understanding of phishing simulation platforms and their capabilities. Understanding routine testing and the important metrics to capture to understand training effectiveness and identify potential risks. 
