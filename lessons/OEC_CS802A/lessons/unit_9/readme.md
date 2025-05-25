## **Electronic Data Interchange (EDI)**

**Definition:**
Electronic Data Interchange (EDI) is the structured transmission of business documents between organizations by electronic means, using standardized message formats without human intervention.

---

### **Meaning & Benefits**

#### **Meaning:**

EDI replaces traditional paper-based communication (e.g., invoices, purchase orders, shipping notices) with automated electronic exchanges between business partners (also called trading partners).

#### **Benefits:**

| **Benefit**               | **Explanation**                                  |
| ------------------------- | ------------------------------------------------ |
| **Speed**                 | Faster processing of transactions                |
| **Accuracy**              | Eliminates manual data entry errors              |
| **Efficiency**            | Reduces paperwork, mailing costs, and labor      |
| **Security**              | Uses encryption for safe transmission            |
| **Integration**           | Links seamlessly with ERP and SCM systems        |
| **Standardization**       | Uniform formats enable interoperability          |
| **Competitive Advantage** | Enables just-in-time delivery, leaner operations |

---

### **Concepts & Applications**

#### **Concepts:**

* **Trading Partner Agreement (TPA):** Legal agreement defining rules for EDI transactions
* **Mapping:** Conversion between internal data formats and EDI standards
* **Translation Software:** Converts business documents to/from EDI formats

#### **Applications:**

| **Industry**      | **Typical Uses**                         |
| ----------------- | ---------------------------------------- |
| **Retail**        | Orders, invoices, shipping notices       |
| **Manufacturing** | Supply orders, parts inventory, invoices |
| **Healthcare**    | Insurance claims, patient records        |
| **Logistics**     | Shipment schedules, bills of lading      |
| **Government**    | Tax filings, procurement                 |

---

### **EDI Model & Protocols**

#### **Models:**

| **Model**                             | **Description**                                           |
| ------------------------------------- | --------------------------------------------------------- |
| **Direct EDI (Point-to-Point)**       | One-to-one connections between trading partners           |
| **EDI via VAN (Value Added Network)** | Third-party service provider relays EDI messages          |
| **Web-based EDI**                     | Browser-accessed EDI portals for small businesses         |
| **Cloud EDI / AS2**                   | Modern internet-based EDI using secure protocols like AS2 |

#### **Protocols:**

| **Protocol**      | **Function**                                |
| ----------------- | ------------------------------------------- |
| **AS1, AS2, AS3** | Secure file transmission over the internet  |
| **FTP/SFTP**      | File transfer with/without encryption       |
| **HTTP/HTTPS**    | Web-based transmission of EDI documents     |
| **OFTP**          | Standard used in European automotive sector |

---

### **UN/EDIFACT & ANSI X12**

| **Standard**   | **Region/Use** | **Maintained by**        | **Features**                                                        |
| -------------- | -------------- | ------------------------ | ------------------------------------------------------------------- |
| **UN/EDIFACT** | International  | United Nations           | Widely used in Europe and globally; supports many message types     |
| **ANSI X12**   | North America  | ASC X12 Committee (ANSI) | Common in US industries like retail, transportation, and healthcare |

**Comparison:**

* UN/EDIFACT uses segments and data elements.
* ANSI X12 uses transaction sets and data segments.
* Conversion tools are available between formats.

---

### **Data Encryption (DES, RSA)**

#### **Need for Encryption in EDI:**

To protect sensitive business information from tampering, unauthorized access, and ensure integrity and authenticity of transactions.

| **Encryption Type**                | **Explanation**                                                                |
| ---------------------------------- | ------------------------------------------------------------------------------ |
| **DES (Data Encryption Standard)** | Symmetric key algorithm; now mostly obsolete due to key length vulnerabilities |
| **RSA (Rivest-Shamir-Adleman)**    | Asymmetric key algorithm; used for digital signatures and secure key exchange  |

#### **Security Measures in EDI:**

* Message authentication codes (MACs)
* Digital signatures (using RSA)
* Public Key Infrastructure (PKI)
* Secure protocols (HTTPS, AS2)

---
