# Botium Toys IT Audit Report

## Company Overview
Botium Toys is a small U.S. business that develops and sells toys. The company has a single physical location serving as office, storefront, and warehouse. Their online presence has grown, attracting customers in the U.S. and abroad, increasing pressure on the IT department to support worldwide operations.

The IT manager initiated an internal audit using the NIST Cybersecurity Framework (CSF) to identify risks, threats, and vulnerabilities, and to ensure compliance with relevant regulations including GDPR and PCI DSS.

---

## Controls Assessment Checklist

| Control | Yes | No |
|---------|-----|----|
| Least Privilege |  | No |
| Disaster recovery plans |  | No |
| Password policies |  | No |
| Separation of duties |  | No |
| Firewall | Yes |  | 
| Intrusion Detection System (IDS) |  | No |
| Backups |  | No |
| Antivirus software | Yes |  |
| Manual monitoring, maintenance, and intervention for legacy systems | | No |
| Encryption |  | No |
| Password management system |  | No |
| Locks (offices, storefront, warehouse) | Yes |  |
| Closed-circuit television (CCTV) surveillance | Yes |  |
| Fire detection/prevention (fire alarm, sprinkler system, etc.) | Yes |  |

---

## Compliance Checklist

### Payment Card Industry Data Security Standard (PCI DSS)

| Best Practice | Yes | No |
|---------------|-----|----|
| Only authorized users have access to customers’ credit card information |  | No |
| Credit card information is stored, accepted, processed, and transmitted internally, in a secure environment |  | No |
| Implement data encryption procedures to better secure credit card transaction touchpoints and data |  | No |
| Adopt secure password management policies |  | No |

### General Data Protection Regulation (GDPR)

| Best Practice | Yes | No |
|---------------|-----|----|
| E.U. customers’ data is kept private/secured |  | No |
| There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach | Yes |  |
| Ensure data is properly classified and inventoried |  | No |
| Enforce privacy policies, procedures, and processes to properly document and maintain data | Yes |  |

### System and Organization Controls (SOC type 1, SOC type 2)

| Best Practice | Yes | No |
|---------------|-----|----|
| User access policies are established |  | No |
| Sensitive data (PII/SPII) is confidential/private |  | No |
| Data integrity ensures the data is consistent, complete, accurate, and has been validated | Yes |  |
| Data is available to individuals authorized to access it | | No |

---

## Recommendations

1. Restrict data access to authorized users only, enforcing least privilege and separation of duties.  
2. Deploy an Intrusion Detection System (IDS) to detect and respond to security threats.  
3. Implement regular backups and a disaster recovery plan to protect critical data.  
4. Encrypt sensitive customer information, including personal and payment data.  
5. Enforce strong password policies with a centralized password management system.  
6. Maintain GDPR-compliant privacy policies and secure all customer and internal data.  
7. Conduct periodic security audits and system monitoring to identify risks early.  
8. Provide employee cybersecurity training to reduce human-error risks.

---

## Conclusion
Botium Toys has basic security measures in place, including firewalls, antivirus, and physical security controls. However, improvements are needed in access control, encryption, intrusion detection, disaster recovery, password management, and compliance with GDPR and PCI DSS. Implementing the recommendations above will strengthen the company's security posture and regulatory compliance.
