# CS-305-Portfolio
Portfolio repository for CS-305: Software Security 

Client and Requirements
The client, Artemis Financial, is a financial services company that needed its software communications to be secure. They requested an HTTPS-enabled server and a secure hash generation process to ensure confidentiality, integrity, and authentication for client data.

Success in Finding Vulnerabilities
I successfully identified outdated dependencies and implemented encryption through SSL and SHA-256 hashing. Secure coding ensures customer trust and prevents breaches, which adds major value to a company’s reputation and system reliability.

Challenges and Insights
The most challenging part was running the OWASP Dependency Check and resolving port conflicts in the SSL configuration. These steps helped me understand how small misconfigurations can weaken security layers.

Increasing Layers of Security
I added security by configuring SSL certificates, implementing HTTPS, and verifying secure communication through checksum validation. In future projects, I would use automated vulnerability scanners like OWASP ZAP and dependency-check plugins to continuously assess risks.

Functionality and Verification
After refactoring, I ensured the code executed without errors by running Maven build tests and verifying that the application launched successfully over HTTPS. I then reviewed the dependency-check report to confirm there were no new vulnerabilities.

Helpful Resources and Tools
Tools such as Maven, OWASP Dependency Check, and the Spring Boot framework were key. These helped automate testing and manage dependencies efficiently for secure development.

Showcasing to Employers
This project demonstrates my ability to secure applications, configure encryption, and apply vulnerability assessment tools—skills that directly apply to software security and DevSecOps roles.
