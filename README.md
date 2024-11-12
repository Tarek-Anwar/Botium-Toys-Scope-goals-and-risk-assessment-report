# Botium Toys Internal Security Audit
## Introduction
**An internal security audit assessment conducted on Botium Toys, a fictitious toy company, completed as part of my cybersecurity portfolio and as part of Google's Cybersecurity Professional Certificate on Coursera in the Play It Safe: Security Risks Management Course.
It is with this in mind that this audit seeks to assess the state of cybersecurity in the company and synchronize current business practices in Botium Toys with those applicable in cybersecurity.  This present document outlines critical risks, recommendations on these risks, and offers a general approach to fortify the organization’s security status. audit report contains the results of the audit, contains a description of measures to address identified issues, and contains descriptions of communication with stakeholders.**

## Scenario
Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide.
The manager of the IT department has decided that an internal IT audit needs to be conducted. She's worried about maintaining compliance and business operations as the company grows without a clear plan. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).  
The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

## Executive Summary
Results of the current analysis reveal that the security controls and compliance practices of Botium Toys have critical control gaps that increase the organization’s security risks.  Lack of proper methods for access control, insufficient data protection, improper reaction to incidents, and improper disaster management plan make the company exposed to data leakage, violation of PCI DSS and GDPR, and revenue loss due to a brand reputation decline.  The following outcomes of audit findings, prioritized recommendations, and improvement plan are described in this report.


## Scope and Goals

**Scope:** 
These audit findings look at all aspects of the company’s security program – its assets (employee’s devices, networks, systems) and controls, as well as all compliances.

**Goals:**

* To implement security controls it is important to * Evaluate current strengths and weaknesses of IT security controls.
* The seventh step was to complete a controls and compliance checklist.
* Critic and find out what has to be changed or improved in order to make the security of the Botium Toys better.
* Give specific advisories to reduce on high risk vulnerabilities.

## Risk Assessment Summary
The present risk evaluation shows insufficient asset management, absence of proper security measures, and regulatory policies.** Current-of-the-mill employees have access to the following information: customer PII data and possibly cardholder data.ropriate security controls and compliance practices.  Key risks include:

* **Unauthorized Data Access:**  All employees currently have access to sensitive data, including customer PII and potentially cardholder data.
* **Lack of Encryption:** Card holder information as well as other sensitive data is not sufficiently encrypted.** Inadequate access controls and passwords, detection and mitigation of intrusions, reaction to security events and disaster preparedness.** Lack of compliance with the PCI DSS and GDPR.ssment highlights inadequate asset management and a lack of appropriate security controls and compliance practices.  Key risks include:
* **Unauthorized Data Access:**  All employees currently have access to sensitive data, including customer PII and potentially cardholder data.
* **Lack of Encryption:** Sensitive data, particularly cardholder information, is not adequately encrypted.
* **Missing Security Controls:**  Weaknesses in access controls, password management, intrusion detection, incident response, and disaster recovery.
* **Compliance Deficiencies:**  Potential non-compliance with PCI DSS and GDPR.

## Controls Assessment Checklist

| Control                               | Status | Notes                                                                  |
|----------------------------------------|--------|-----------------------------------------------------------------------|
| Least Privilege                       | ❌      | Not implemented. All employees have access to sensitive data.        |
| Disaster Recovery Plans                | ❌      | No disaster recovery plan exists.                                       |
| Password Policies                     | ⚠️      | Policy exists but is inadequate (weak complexity requirements).        |
| Separation of Duties                  | ❌      | Not implemented.                                                        |
| Firewall                              | ✅      | Firewall in place, but configuration details require further review.  |
| Intrusion Detection System (IDS)       | ❌      | No IDS implemented.                                                   |
| Backups                               | ❌      | No regular backups performed.                                         |
| Antivirus Software                     | ✅      | Antivirus software installed, but effectiveness needs assessment.      |
| Legacy System Monitoring/Maintenance  | ⚠️      | Monitoring exists but lacks a consistent schedule and process.      |
| Encryption                             | ❌      | Encryption not implemented for sensitive data.                        |
| Password Management System            | ❌      | No centralized password management system.                             |
## Compliance Checklist

**PCI DSS:**

* **Authorized Access Only:** ❌
* **Secure Storage/Processing/Transmission:** ❌
* **Data Encryption:** ❌
* **Secure Password Management:** ⚠️ *(Existing policy is weak)*

**GDPR:**

* **EU Customer Data Privacy:** ❌ 
* **72-Hour Breach Notification:** ✅
* **Data Classification/Inventory:** ❌
* **Privacy Policies/Procedures:** ⚠️

## Remediation Recommendations

**High Priority:**

1. **Implement Data Encryption and Access Controls:** Protect completed and unfinished work with security precautions (card holder data, PII data) both during storage and during transmission.  Administrative controls involve least privilege and separation of duties.  Identify potential problem areas to cover compliance to PCI DSS.** Develop and simulate sound strategies for managing emergencies and recoveries in case of unfavorable incidences such as computer failures and hacking and data backup.sensitive data (cardholder data, PII) at rest and in transit.  Implement least privilege and separation of duties.  Address PCI DSS compliance gaps.

2. **Develop and Implement Incident Response and Disaster Recovery Plans:**  Create and test comprehensive plans for incident response and disaster recovery, including regular data backups.

3. **Strengthen Password Management:** Use of appropriate password management standards and policies; password strengths and ensure compliance with password standards; deployment of a sound password management system.

**Medium Priority:**

4. **Enhance Security Monitoring and Detection:** Deploy an IDS, create the centralized logging, and perform vulnerability assessment and pen testing presence on a daily basis.

5. **Expand Security Awareness Training:** Security awareness training should be made with accessibility to all the staff.

6. **Formalize Data Classification and Inventory:** Every IT asset and datum must be effectively cataloged and comprehensively enumerated.  Address GDPR compliance gaps.
## Stakeholders Secured

Iterating communication is necessary so that you can remain informed before, during and after the crisis.  The IT manager should share the audit result and proposed measures to the top management by illustrating the possible consequence and the necessity of spending on enhancing security.  That is why it is necessary to suggest a step by step approach to implementing the recommendations in the framework of a reasonable time line and with reasonable budgetary provisions.  The stakeholders should be informed, progress and further communication should be reported.


## Conclusion

The security opinions of Botium Toys show that it is necessary to urgently eliminate the identified risks in the field of information security and compliance.  Mastering the recommendations of this report would allow Botium Toys to enhance considerably its security level in the face of the various threats it is facing in order to safeguard its secret business information, and avoid adverse financial or image losses incidents.  This entails commitment from the organization’s leadership to support security expenses and take security as an important concern to all the sub-teams.
