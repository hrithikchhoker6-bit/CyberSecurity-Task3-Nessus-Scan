# 🔐 Cyber Security Internship – Task 3  
## Vulnerability Assessment using Nessus Essentials  

### 🧰 Tool Used  
**Nessus Essentials** by Tenable  

### 🕹️ Objective  
To perform a vulnerability assessment on a target system using Nessus Essentials, analyze the results, and understand common security risks.

---

### ⚙️ Steps Performed  

1. **Installed Nessus Essentials**
   - Downloaded from the official Tenable website.  
   - Activated using a free license key.  

2. **Performed Basic Network Scan**
   - Target IP: `10.187.11.4`  
   - Policy: *Basic Network Scan*  
   - Duration: ~8 minutes  

3. **Results**
   - Total Vulnerabilities Detected: 22  
   - Example:  
     - **SSL Certificate Cannot Be Trusted**  
       - *Severity:* Medium (CVSS 6.5)  
       - *Impact:* Server certificate is self-signed or not issued by a trusted CA.  
       - *Solution:* Install a valid CA-signed certificate.  

---

### 📊 Summary  
| Severity | Count |
|-----------|-------|
| 🔴 Critical | 1 |
| 🟠 High | 3 |
| 🟡 Medium | 10 |
| 🔵 Low | 8 |

**Conclusion:**  
Nessus Essentials successfully identified multiple misconfigurations and SSL issues. Regular vulnerability scanning helps in early detection and mitigation of potential threats.

---

### 📎 Files Included  
- `Task3_Nessus_Report.nessus` – Exported scan report from Nessus  
- `README.md` – Documentation  

---

### 👨‍💻 Author  
**Hrithik Chhoker**
