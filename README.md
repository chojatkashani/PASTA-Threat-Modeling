# PASTA-Threat-Modeling: AppDev



---

## **Stages of PASTA Security Analysis**  

### **I. Define Business and Security Objectives**  
**Key Business Requirements:**  
- Users can **create member profiles** internally or by **connecting external accounts**.  
- The app must **process financial transactions**.  
- The app should **comply with PCI-DSS** security standards.  

---

### **II. Define the Technical Scope**  
**Technologies Used in the Application:**  
- **Application Programming Interface (API)**  
- **Public Key Infrastructure (PKI)**  
- **Advanced Encryption System (AES)**  
- **SHA-256**  
- **SQL**  

**API Security Considerations:**  
APIs **exchange data** between customers, partners, and employees, making them a **high-priority security concern**.  
- APIs **handle sensitive data** and **connect multiple systems**.  
- The **attack surface is larger**, making them **prone to vulnerabilities**.  
- **Identifying which APIs are in use** is crucial before **prioritizing security efforts**.  

---

### **III. Decompose Application**  
**Sample Data Flow Diagram**  
<img width="600" alt="Screenshot 2025-02-06 at 8 30 17 PM" src="https://github.com/user-attachments/assets/0719903e-90ff-4e42-b3e7-eeda6f460c08" />


---

### **IV. Threat Analysis**  
**Potential Threats Identified in the PASTA Worksheet:**  
1. **Injection Attacks** (SQL Injection, Command Injection)  
2. **Session Hijacking** (Exploiting insecure session handling)  

---

### **V. Vulnerability Analysis**  
**Identified Vulnerabilities in the PASTA Worksheet:**  
1. **Lack of Prepared Statements** (Prone to SQL Injection)  
2. **Broken API Token** (Leads to unauthorized access)  

---

### **VI. Attack Modeling**  
**Sample Attack Tree Diagram**  
<img width="591" alt="Screenshot 2025-02-06 at 8 30 33 PM" src="https://github.com/user-attachments/assets/1a78bd43-fdf7-4ca9-9f58-d241c86e7b97" />

---

### **VII. Risk Analysis and Impact**  
**Security Controls to Reduce Risk:**  
1. **SHA-256** (Ensures data integrity and secure hashing)  
2. **Incident Response Procedures** (Ensures quick mitigation of security threats)  
3. **Password Policy** (Enforces strong authentication practices)  
4. **Principle of Least Privilege** (Limits access rights based on necessity)  

---  

## **Summary**  
By following the **PASTA methodology**, the **sneaker company** can identify **security risks, threats, and vulnerabilities** while implementing **controls to mitigate risks** effectively. 🚀  
