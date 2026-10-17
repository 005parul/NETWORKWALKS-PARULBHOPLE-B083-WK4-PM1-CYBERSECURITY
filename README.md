<div align="center">

🔐 Week 4 — Web Application Penetration Testing
SQL Injection, Access Control, and Sensitive Document Security
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Cybersecurity-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Week-04-0070C0?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Web%20Security-C00000?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/SQL%20Injection-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Penetration%20Testing-0070C0?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/NetworkWalks-C00000?style=flat-square&labelColor=000000" />
</p>

## 📌 Overview
This Week 4 project, completed as part of the NETWORKWALKS Cybersecurity Program (Batch B083), focused on assessing web application security, analyzing SQL injection risks, reviewing access controls, and understanding the protection of sensitive documents.

## 🎯 Objectives
- Assess web application behavior and identify potential security weaknesses.
- Understand SQL injection and its possible impact.
- Review access controls protecting restricted documents.
- Evaluate document-protection considerations.
- Document findings and recommend practical security improvements.
- 
## 🛡️ Scope & Ethical Use
Testing was performed as part of the assigned educational exercise and must remain within the explicitly authorized scope. No testing should be conducted against systems without permission. Sensitive documents, credentials, patient information, and confidential technical details must not be published.

## 🧰 Tools & Techniques
- cURL: HTTP response and redirect inspection.
- Web application testing: Review of application inputs and behavior.
- SQL injection assessment: Evaluation of input-handling weaknesses within the authorized exercise.
- Security reporting: Documentation of observations, potential impact, and remediation.
- NetworkWalks hash cracking and password cracking website
  
## 🔎 Key Activities
1. Performed initial web reconnaissance and reviewed application responses.
2. Examined application entry points and input handling.
3. Assessed a reported SQL injection issue in the training exercise.
4. Reviewed access controls around restricted PDF documents.
5. Documented potential risks and security recommendations.
   
## 📊 Key Findings
- SQL injection risk: Unsafe input handling may allow unintended database interactions.
- Access-control risk: Restricted documents should be protected by server-side authorization checks.
- Document protection: Encryption and access authorization serve different purposes and should be implemented together.
- Information disclosure: Publicly exposed technology metadata may assist fingerprinting but does not independently confirm a vulnerability.
Severity should be assigned only after validating the findings against the test results and assessing the actual impact.

## 🔐 Recommendations
- Use parameterized queries and prepared statements to prevent SQL injection.
- Enforce server-side authorization for every protected resource.
- Store sensitive files securely and restrict direct public access.
- Apply appropriate encryption and protect encryption keys.
- Keep application components updated and monitor suspicious activity.
- Retest after remediation to confirm that weaknesses have been addressed.
  
## 🧠 What I Learned
This project strengthened my understanding of web application testing, SQL injection risks, server-side access control, sensitive document protection, and structured penetration-testing reports. It also reinforced the importance of authorized testing and responsible handling of confidential information.

🔗 Resources
- NetworkWalks cracking websites
- Sample hospital website
- Kali Linux

## 👤 Author

Parul Bhople

Cybersecurity Intern, 
Networkwalks

LinkedIn: https://www.linkedin.com/in/parul-b-b7b4a22a8/
