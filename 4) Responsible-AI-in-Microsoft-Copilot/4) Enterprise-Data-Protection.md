# How Data Protection Restricts Prompt Results in Microsoft 365 Copilot

## 1. Overview

Microsoft 365 Copilot enforces data protection mechanisms that directly impact what information can be accessed and returned in prompt responses.

These controls ensure:
- Data privacy
- Security compliance
- Controlled access to sensitive information

---

## 2. Enterprise Data Protection (EDP)

Copilot Chat operates under Enterprise Data Protection.

### Key Characteristics

- Data is encrypted:
  - At rest (while stored)
  - In transit (while moving between services)

- Data remains private:
  - Not used by Microsoft for training
  - Not used to train foundational models (e.g., GPT)

- Access is governed by:
  - Organizational policies
  - User permissions

- Protection against:
  - Harmful content
  - Prompt injection attacks

---

## 3. Access-Based Data Restrictions

### 3.1 Permission-Based Access

Copilot can only access data that the user has permission to view.

### Example

- If a user does not have access to a SharePoint folder:
  - The user cannot access it manually
  - Copilot cannot access it on their behalf

---

### 3.2 Implication

- Copilot inherits user permissions
- It does not elevate access privileges

---

### 3.3 Risk Consideration

If users are granted unnecessary access:

- Copilot may use that data in responses
- Sensitive data exposure risk increases

---

### Recommendation

- Ensure users only have access to required data
- Regularly review permissions

---

## 4. Sensitivity Labels

Microsoft Purview Information Protection uses sensitivity labels to classify and protect data.

### Examples of Labels

- Highly Confidential
- Confidential
- No Sensitivity

---

### Functionality

- Labels define access restrictions
- Can be combined with policies
- Control how data is:
  - Accessed
  - Shared
  - Processed

---

### Impact on Copilot

- Copilot respects sensitivity labels
- Data with higher sensitivity may have stricter access controls
- Limits what can be included in prompt responses

---

## 5. Combined Effect on Prompt Results

Data protection restricts Copilot responses through:

- User access permissions
- Organizational policies
- Sensitivity labels
- Encryption and security controls

---
