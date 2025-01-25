# Cheat Sheet: CISSP Domain 8 - Software Development Security

This cheat sheet provides a concise summary of key concepts, frameworks, and tools related to CISSP Domain 8, focused on secure software development practices.

---

## **1. Secure Software Development Lifecycle (SDLC)**

### Phases:
1. **Requirements**: Define functional and security requirements.
2. **Design**: Apply secure design patterns and architecture.
3. **Implementation**: Adhere to secure coding practices.
4. **Testing**: Conduct static and dynamic analysis.
5. **Deployment**: Harden configurations and secure environments.
6. **Maintenance**: Patch vulnerabilities and monitor security incidents.

### Key Practices:
- **Shift Left**: Integrate security early in the SDLC.
- **DevSecOps**: Embed security into CI/CD pipelines.

---

## **2. Threat Modeling**

### Frameworks and Techniques:
- **STRIDE**: Spoofing, Tampering, Repudiation, Information Disclosure, Denial of Service, Elevation of Privilege.
- **DREAD**: Damage, Reproducibility, Exploitability, Affected Users, Discoverability.

### Steps:
1. Identify assets.
2. Create architecture diagrams.
3. Identify threats.
4. Assess risk and prioritize.
5. Mitigate risks.

---

## **3. Secure Coding Practices**

### Common Vulnerabilities:
- **SQL Injection**: Use parameterized queries.
- **Cross-Site Scripting (XSS)**: Sanitize inputs and encode outputs.
- **Buffer Overflow**: Use memory-safe languages and perform bounds checking.
- **Cross-Site Request Forgery (CSRF)**: Use anti-CSRF tokens.

### Principles:
- **Input Validation**: Whitelist inputs rather than blacklist.
- **Output Encoding**: Prevent injection attacks.
- **Authentication and Authorization**: Implement MFA and RBAC.

---

## **4. Cryptography Basics**

### Key Concepts:
- **Symmetric Encryption**: Single key (e.g., AES).
- **Asymmetric Encryption**: Public/Private key pair (e.g., RSA).
- **Hashing**: Generate a fixed-length output (e.g., SHA-256).
- **Digital Signatures**: Verify authenticity and integrity.
- **PKI**: Manage digital certificates.

---

## **5. Security Testing and Tools**

### Testing Types:
- **Static Application Security Testing (SAST)**: Analyze source code.
- **Dynamic Application Security Testing (DAST)**: Test running applications.
- **Penetration Testing**: Simulate real-world attacks.

### Tools:
- **SAST Tools**: SonarQube, Fortify.
- **DAST Tools**: OWASP ZAP, Burp Suite.
- **Penetration Testing**: Metasploit, Wireshark.

---

## **6. Compliance and Legal Considerations**

### Standards and Frameworks:
- **GDPR**: Data privacy regulations in the EU.
- **HIPAA**: Protect healthcare information.
- **NIST Framework**: Cybersecurity best practices.

### Ethics:
- Prioritize user privacy and data protection.
- Comply with local and international regulations.

---

## **7. Emerging Trends**

### Key Topics:
- **AI in Security**: Automated threat detection and anomaly analysis.
- **Quantum Computing**: Development of quantum-resistant cryptography.
- **IoT Security**: Secure device communication and control.

---

## **How to Use This Cheat Sheet**
- Refer to this document for quick revisions before the exam.
- Pair with practice questions to solidify your understanding.
- Use tools like OWASP ZAP or SonarQube for hands-on experience.

Good luck with your studies!

