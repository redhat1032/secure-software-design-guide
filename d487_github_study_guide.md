\# Comprehensive Study Guide for Secure Software Design (D487 \+ CISSP Domain 8\)

 

This guide is designed to help you prepare for the \*\*WGU D487 Secure Software Design exam\*\* and understand key topics from \*\*Domain 8 of the CISSP\*\*. The guide covers fundamental concepts practical applications, and includes study questions, cheat sheets, and tools to solidify your knowledge.

 

\---

 

\#\# \*\*Table of Contents\*\*

 

1\. \[Introduction to Secure Software Design\](\#introduction)

2\. \[Secure Software Development Lifecycle (SDLC)\](\#sdlc)

3\. \[Threat Modeling and Risk Assessment\](\#threat-modeling)

4\. \[Core Secure Coding Practices\](\#secure-coding)

5\. \[Cryptography Basics\](\#cryptography)

6\. \[Security Testing and Validation\](\#testing)

7\. \[Secure Software Architecture and Design\](\#architecture)

8\. \[Compliance, Ethics, and Emerging Trends\](\#compliance)

9\. \[Practice Questions\](\#practice-questions)

10\. \[Cheat Sheet: CISSP Domain 8\](\#cissp-cheat-sheet)

11\. \[Resources and Tools\](\#resources)

 

\---

 

\#\# \*\*1. Introduction to Secure Software Design\*\* \<a name="introduction"\>\</a\>

 

\#\#\# Key Concepts

\- \*\*Secure Software Design\*\*: Integrates security considerations at every stage of development.

\- \*\*Functional vs. Non-Functional Requirements\*\*:

  \- Functional: User logins, payment processing.

  \- Non-Functional: Encryption, performance, and scalability.

 

\#\#\# Core Principles

\- \*\*CIA Triad\*\*:

  \- \*\*Confidentiality\*\*: Protect sensitive data.

  \- \*\*Integrity\*\*: Ensure data accuracy and trustworthiness.

  \- \*\*Availability\*\*: Ensure reliable access.

\- \*\*Least Privilege\*\*: Limit access rights to essential functions.

\- \*\*Fail-Safe Defaults\*\*: Default systems to the most secure state.

\- \*\*Defense in Depth\*\*: Multiple layers of security controls.

\- \*\*Open Design\*\*: Transparency over obscurity.

 

\---

 

\#\# \*\*2. Secure Software Development Lifecycle (SDLC)\*\* \<a name="sdlc"\>\</a\>

 

\#\#\# Phases and Security Considerations

1\. \*\*Requirements\*\*:

   \- Define functional and security requirements.

   \- Perform initial risk assessments.

2\. \*\*Design\*\*:

   \- Apply secure design patterns.

   \- Architect for defense-in-depth.

3\. \*\*Implementation\*\*:

   \- Enforce secure coding practices.

   \- Conduct code reviews.

4\. \*\*Testing\*\*:

   \- Use SAST and DAST tools.

   \- Perform penetration testing.

5\. \*\*Deployment\*\*:

   \- Harden configurations.

   \- Implement runtime protections.

6\. \*\*Maintenance\*\*:

   \- Regular updates and vulnerability patching.

   \- Monitor and log security incidents.

 

\#\#\# DevSecOps Practices

\- \*\*CI/CD Pipelines\*\*: Automate security testing.

\- \*\*Collaboration\*\*: Integrate security into development workflows.

\- \*\*Tooling\*\*: Utilize tools like OWASP ZAP for continuous testing.

 

\---

 

\#\# \*\*3. Threat Modeling and Risk Assessment\*\* \<a name="threat-modeling"\>\</a\>

 

\#\#\# Threat Modeling Techniques

\- \*\*Steps\*\*:

  1\. Identify assets.

  2\. Diagram system architecture.

  3\. Decompose applications.

  4\. Identify threats using STRIDE.

  5\. Document and mitigate threats.

 

\- \*\*STRIDE\*\*:

  \- \*\*Spoofing\*\*: Pretending to be another entity.

  \- \*\*Tampering\*\*: Modifying data.

  \- \*\*Repudiation\*\*: Denying an action.

  \- \*\*Information Disclosure\*\*: Leaking sensitive data.

  \- \*\*Denial of Service\*\*: Disrupting access.

  \- \*\*Elevation of Privilege\*\*: Gaining unauthorized access.

 

\#\#\# Risk Assessment

\- \*\*Risk Formula\*\*:

  \\\[ \\text{Risk} \= \\text{Likelihood} \\times \\text{Impact} \\\]

\- \*\*Controls\*\*: Encryption, monitoring, access restrictions.

 

\---

 

\#\# \*\*4. Core Secure Coding Practices\*\* \<a name="secure-coding"\>\</a\>

 

\#\#\# Common Vulnerabilities and Mitigation

\- \*\*SQL Injection\*\*:

  \- Use parameterized queries.

  \- Validate user input.

\- \*\*Cross-Site Scripting (XSS)\*\*:

  \- Sanitize inputs.

  \- Encode outputs.

\- \*\*Buffer Overflow\*\*:

  \- Use memory-safe languages (e.g., Rust).

  \- Implement bounds checking.

\- \*\*CSRF\*\*:

  \- Use anti-CSRF tokens.

  \- Validate HTTP request origins.

 

\#\#\# Coding Standards

\- \*\*Input Validation\*\*: Whitelist preferred over blacklist.

\- \*\*Error Handling\*\*: Log securely without exposing sensitive details.

\- \*\*Authentication\*\*: Implement MFA and RBAC.

 

\---

 

\#\# \*\*5. Cryptography Basics\*\* \<a name="cryptography"\>\</a\>

 

\#\#\# Encryption

\- \*\*Symmetric\*\*: Uses a single key (e.g., AES).

\- \*\*Asymmetric\*\*: Uses a public/private key pair (e.g., RSA).

 

\#\#\# Hashing

\- \*\*Properties\*\*: Deterministic, collision-resistant.

\- \*\*Algorithms\*\*: SHA-256, SHA-3.

 

\#\#\# Digital Signatures

\- \*\*Purpose\*\*: Verify authenticity and integrity.

\- \*\*PKI\*\*: Manages digital certificates.

 

\---

 

\#\# \*\*6. Security Testing and Validation\*\* \<a name="testing"\>\</a\>

 

\#\#\# Testing Approaches

\- \*\*SAST\*\*: Analyze source code for vulnerabilities.

\- \*\*DAST\*\*: Test running applications for runtime issues.

\- \*\*Penetration Testing\*\*: Simulate real-world attacks.

 

\#\#\# Tools

\- \*\*SAST\*\*: SonarQube, Fortify.

\- \*\*DAST\*\*: OWASP ZAP, Burp Suite.

\- \*\*Penetration Testing\*\*: Metasploit, Wireshark.

 

\---

 

\#\# \*\*7. Secure Software Architecture and Design\*\* \<a name="architecture"\>\</a\>

 

\#\#\# Principles

\- \*\*Modularity\*\*: Isolate components to reduce attack surface.

\- \*\*Encapsulation\*\*: Restrict internal component access.

\- \*\*Abstraction\*\*: Simplify complex systems for better security.

 

\#\#\# Defense in Depth

\- \*\*Layered Controls\*\*: Firewalls, encryption, intrusion detection.

\- \*\*Monitoring\*\*: Continuous logging and anomaly detection.

 

\---

 

\#\# \*\*8. Compliance, Ethics, and Emerging Trends\*\* \<a name="compliance"\>\</a\>

 

\#\#\# Compliance Standards

\- \*\*GDPR\*\*: Data privacy in the EU.

\- \*\*HIPAA\*\*: Protect healthcare information.

\- \*\*NIST Frameworks\*\*: Cybersecurity best practices.

 

\#\#\# Emerging Trends

\- \*\*AI in Security\*\*: Automating threat detection.

\- \*\*Quantum Computing\*\*: Quantum-resistant cryptography.

\- \*\*IoT Security\*\*: Harden device communication and controls.

 

\---

 

\#\# \*\*9. Practice Questions\*\* \<a name="practice-questions"\>\</a\>

 

Check out the \[Practice Questions Sheet\](\#) for scenario-based and multiple-choice questions.

 

\---

 

\#\# \*\*10. Cheat Sheet: CISSP Domain 8\*\* \<a name="cissp-cheat-sheet"\>\</a\>

 

Find the detailed \*\*CISSP Domain 8 Cheat Sheet\*\* \[here\](\#).

 

\---

 

\#\# \*\*11. Resources and Tools\*\* \<a name="resources"\>\</a\>

 

\#\#\# Tools

\- \*\*OWASP ZAP\*\*: Dynamic application testing.

\- \*\*SonarQube\*\*: Static code analysis.

\- \*\*Metasploit\*\*: Penetration testing.

 

\#\#\# Further Reading

\- \[OWASP Secure Coding Practices\](https://owasp.org/)

\- \[NIST Cybersecurity Framework\](https://www.nist.gov/cyberframework)

\- \[WGU Study Resources\](https://www.wgu.edu/)

 

\---

 

\*\*Contribute to This Guide\*\*: Fork this repository, make updates, and submit a pull request\!

