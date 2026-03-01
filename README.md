# Southern New Hampshire University<br><br>CS-255: Software Security

This is a repository to demonstrate the skills and techniques learned in CS-305 Software Security. This project represents more than just a completed assignment; it reflects my ability to analyze software from a security-focused perspective, identify vulnerabilities, and implement practical mitigation strategies in a real-world context. Through this experience, I strengthened my understanding of secure coding principles, encryption algorithms, hashing techniques, certificate generation, and layered security implementation.

Throughout this project, I learned how to evaluate risk, apply cryptographic protections appropriately, and verify that security enhancements do not compromise system functionality. I gained practical experience in assessing vulnerabilities, refactoring code securely, and validating that implemented security controls effectively protected sensitive data. This process reinforced the importance of thinking proactively about security rather than treating it as an afterthought.

Moving forward, I will apply these skills to future development projects by prioritizing secure design from the beginning of the software development lifecycle. I plan to use vulnerability assessment tools, secure coding standards, and layered defense strategies to ensure confidentiality, integrity, and availability remain foundational components of any system I build.

## Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial was a financial services company that required improved application security to protect sensitive customer financial data. The company needed to address vulnerabilities related to insecure communication and data integrity within its software. The primary objective was to implement secure communication protocols, apply proper encryption and hashing techniques, and ensure the system met modern security standards to safeguard client information.

## What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

I effectively analyzed the existing codebase to identify weaknesses in encryption and secure communications. I implemented HTTPS, applied secure hashing algorithms, and ensured proper certificate configuration to strengthen the application’s defenses. Coding securely is essential because financial systems handle highly sensitive data, and vulnerabilities can lead to data breaches, financial loss, and reputational damage. Strong software security protects confidentiality, integrity, and availability while increasing customer trust and regulatory compliance.

## Which part of the vulnerability assessment was challenging or helpful to you?

The most challenging aspect was ensuring that encryption configurations and certificate generation were correctly implemented without disrupting system functionality. However, this was also the most valuable part of the project because it deepened my understanding of cryptographic concepts, public key infrastructure, and how secure communication is established between client and server systems.

## How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I increased layers of security by implementing HTTPS, generating a self-signed certificate, applying secure hashing for checksum verification, and validating secure communication channels. In the future, I would use static code analysis tools, dependency vulnerability scanners, and automated security testing frameworks to identify weaknesses. I would also reference secure development frameworks and risk assessment methodologies to determine appropriate mitigation strategies.

## How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

After refactoring, I recompiled the application, tested secure connections, verified checksum generation, and reviewed the code to ensure encryption and hashing were functioning correctly. I validated that the application maintained its intended functionality while confirming that no new warnings, errors, or insecure configurations were introduced during the security enhancements.

## What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

I used secure coding principles, certificate management tools, hashing algorithms, and encryption best practices to complete this project. Understanding symmetric versus asymmetric encryption, implementing collision-resistant hash functions, and applying layered security strategies will continue to be valuable in future development and security-focused tasks.

## What might you show future employers from this assignment?

I would show future employers my vulnerability assessment process, secure code refactoring, certificate generation, and encryption implementation as evidence of my hands-on experience in software security. This assignment demonstrates my ability to analyze risk, apply cryptographic solutions, test security improvements, and document technical work clearly and professionally.
