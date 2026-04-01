# Recognizing and Mitigating Risks to Sensitive Data

## 1. Overview

Protecting sensitive data is a critical aspect of responsible AI and data governance. Organizations must:

- Identify sensitive data
- Control access and usage
- Prevent unauthorized exposure
- Implement policies and monitoring mechanisms

Microsoft Purview provides tools to help classify, protect, and manage sensitive information.

---

## 2. Types of Sensitive Data

Sensitive data includes multiple categories:

---

### 2.1 Personally Identifiable Information (PII)

Includes:

- Driver’s license numbers
- Passport numbers
- National ID numbers
- Tax identification numbers
- Social security numbers
- Physical addresses

---

### 2.2 Financial Information

Includes:

- Bank account numbers
- Credit card numbers

---

### 2.3 Authentication Secrets

Includes:

- Credentials
- Password-related data

---

### 2.4 Medical and Health Information

Includes:

- Medical conditions
- Health-related records

---

### 2.5 Network and System Information

Includes:

- IP addresses
- SQL server connection strings

---

### 2.6 Location Data

Includes:

- Geographic and location-based information

---

## 3. Identifying Sensitive Data

Organizations can use Microsoft Purview Information Protection to:

- Detect sensitive information types
- Classify data automatically
- Monitor data across systems

---

### Data Locations Covered

- SharePoint Online
- OneDrive for Business
- Exchange (email)
- Microsoft Teams
- Copilot environments

---

## 4. Key Risk Areas

Sensitive data risks include:

- Unauthorized access
- Data leakage
- Excessive data storage
- Improper sharing
- Weak access controls
- Lack of monitoring

---

## 5. Mitigation Strategies

---

### 5.1 Data Minimization

- Do not store sensitive data unless necessary
- Remove unnecessary data from systems

---

### 5.2 Access Control

- Use Role-Based Access Control (RBAC)
- Ensure only authorized users can access data

---

### 5.3 Principle of Least Privilege

- Grant users only the minimum access required
- Avoid excessive permissions

---

### 5.4 Monitoring and Auditing

- Track who accesses data
- Monitor when and why data is accessed
- Maintain audit logs

---

### 5.5 Restrict Data Usage

- Prevent uncontrolled downloads
- Limit export capabilities
- Control sharing permissions

---

### 5.6 Data Masking and Encryption

- Encrypt data:
  - In transit
  - At rest

- Mask sensitive data where possible:
  - Example: Show only last four digits of a credit card number

---

### 5.7 Data Segmentation

- Avoid storing all sensitive data in one place
- Use smaller datasets to reduce exposure risk

---

### 5.8 Secure Data Merging

- Ensure merged datasets maintain security controls
- Do not reduce protection levels when combining data

---

### 5.9 Consistent Data Handling

- Treat records consistently
- Avoid revealing which records contain sensitive data through different handling

---

### 5.10 Sharing Policies

- Define rules for internal and external sharing
- Apply controls across platforms

---

### 5.11 Review System Settings

- Review default Copilot configurations
- Ensure secure data handling settings are applied

---

## 6. Microsoft Purview Capabilities

---

### 6.1 Information Protection

- Identifies and classifies sensitive data
- Applies labels and protection policies

---

### 6.2 Data Explorer

- Allows visibility into sensitive data locations
- Helps monitor data across services

---

### 6.3 Data Loss Prevention (DLP)

- Detects sensitive data usage
- Prevents unauthorized sharing
- Triggers alerts for policy violations

---

## 7. User Awareness and Training

- Educate users on handling sensitive data
- Promote secure data practices
- Reduce human error risks

---

## 8. Key Takeaways

- Sensitive data includes PII, financial, medical, and system information
- Use Microsoft Purview to identify and classify data
- Apply RBAC and least privilege principles
- Monitor and audit data access regularly
- Prevent data leakage through DLP policies
- Segment and secure data storage
- Train users on responsible data handling

---
