## **Risks in E-Commerce**

E-Commerce involves the digital exchange of information, goods, and services, and while it offers convenience and efficiency, it also introduces several security and operational risks.

---

### **Security in E-Commerce**

#### **Definition:**

E-Commerce security refers to the protection of assets during electronic transactions, ensuring confidentiality, integrity, authentication, and availability.

#### **Core Security Principles:**

* **Confidentiality** – Prevent unauthorized access to data
* **Integrity** – Ensure that data is not altered during transmission
* **Authentication** – Verify identities of communicating parties
* **Non-repudiation** – Ensure parties cannot deny transactions
* **Availability** – Ensure systems are operational when needed

#### **Common Threats:**

| **Threat**                  | **Description**                             |
| --------------------------- | ------------------------------------------- |
| **Phishing**                | Fraudulent emails to extract sensitive info |
| **Malware**                 | Viruses, spyware, ransomware                |
| **Man-in-the-middle**       | Intercepting and altering communications    |
| **SQL Injection**           | Malicious SQL to access databases           |
| **Denial-of-Service (DoS)** | Overloading systems to shut down services   |
| **Session Hijacking**       | Taking control of a user's session          |

---

### **Security Standards**

Standard frameworks ensure consistency in how security is implemented in E-Commerce systems.

| **Standard**          | **Purpose**                                                                |
| --------------------- | -------------------------------------------------------------------------- |
| **ISO/IEC 27001**     | Information security management system (ISMS)                              |
| **PCI-DSS**           | Protects cardholder data during transactions                               |
| **TLS/SSL Protocols** | Encrypts data over internet connections                                    |
| **OWASP Top 10**      | Guidelines for addressing top security vulnerabilities in web applications |

---

### **Firewall & Cryptography**

#### **Firewall:**

* **Definition:** A security system that monitors and controls incoming/outgoing network traffic based on predefined rules.
* **Types:**

  * **Packet-filtering firewall**
  * **Stateful inspection firewall**
  * **Proxy firewall**
  * **Next-generation firewall (NGFW)**

#### **Cryptography:**

* **Definition:** The practice of securing information by transforming it into an unreadable format.
* **Types:**

  * **Symmetric-key (e.g., AES)** – Same key for encryption and decryption
  * **Asymmetric-key (e.g., RSA)** – Public-private key pairs
* **Applications in E-Commerce:**

  * Secure checkout
  * Encrypted communication (HTTPS)
  * Digital signatures

---

### **Key Management & Password Systems**

#### **Key Management:**

* Process of generating, exchanging, storing, using, and replacing cryptographic keys
* Includes:

  * Key Generation
  * Distribution
  * Rotation
  * Revocation
* Ensures that encryption systems remain secure and operational

#### **Password Systems:**

* **Strong Password Policy:**

  * Length (8+ characters)
  * Complexity (mix of characters)
  * Periodic changes
* **Enhancements:**

  * Multi-Factor Authentication (MFA)
  * Password hashing (e.g., bcrypt, PBKDF2)
  * Password managers for secure storage

---

### **Digital Certificates & Digital Signatures**

#### **Digital Certificates:**

* Issued by Certificate Authorities (CA)
* Verify ownership of public keys
* Contain:

  * Owner’s public key
  * Owner’s identity
  * CA digital signature
* Used in SSL/TLS protocols (HTTPS)

#### **Digital Signatures:**

* **Purpose:** Ensure message authenticity and integrity
* **How it works:**

  * Sender encrypts message hash with private key
  * Receiver decrypts with public key and verifies the hash
* Based on public-key cryptography (e.g., RSA, DSA)

---
