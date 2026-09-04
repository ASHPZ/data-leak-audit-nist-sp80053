# Data Leak Audit & Security Assessment

## 📝 Project Overview
This project is a simulated cybersecurity audit conducted as part of the Google Cybersecurity Professional Certificate. It analyzes a data leak incident involving internal corporate documents, identifies the root causes related to access management, and provides actionable recommendations to prevent future occurrences.

## 🎯 Objective
To evaluate a data leak incident, review existing security controls, and recommend improvements based on industry frameworks to enhance data privacy and ensure the principle of least privilege is strictly enforced.

## 🔍 Frameworks & Standards Applied
* **NIST SP 800-53**: Security and Privacy Controls for Information Systems and Organizations.
* **Focus Control**: AC-6 (Least Privilege).

## 📊 Incident Summary
A sales manager inadvertently caused a data leak when an internal-only folder was shared with external business partners. The root cause was identified as a violation of the principle of least privilege, compounded by the failure to revoke temporary access post-meeting and the lack of restrictions on external link sharing.

## 🛡️ Recommended Controls (AC-6)
1. **Role-Based Access Control (RBAC)**: Restrict access to sensitive resources strictly based on defined user roles.
2. **Automated Revocation**: Configure automatic access revocation for temporary permissions.
3. **External Sharing Restrictions**: Disable external sharing capabilities for internal directories by default.
4. **Regular Auditing**: Implement continuous monitoring and regular audits of user privileges and access logs.

## 📁 Files Included
* `Data_Leak_Audit_Report.pdf`: The complete, professional audit report containing the incident review, identified issues, and justification for the recommended security enhancements.
