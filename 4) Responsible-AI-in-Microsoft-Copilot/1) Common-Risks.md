# Responsible AI and Data Protection – Common Risks

## 1. Overview

When using Microsoft 365 Copilot and AI systems, it is important to understand common risks related to:

- Accuracy
- Security
- Data protection
- System behavior

These risks can impact decision-making, data integrity, and organizational security.

---

## 2. Fabrications (Hallucinations)

### Definition

Fabrications, also known as hallucinations, occur when AI generates responses that:

- Are not based on input data
- Are not grounded in factual information
- May appear confident but are incorrect

---

### Example Behavior

- AI provides inconsistent or contradictory answers
- Responses may change when questioned again
- Information may appear plausible but be inaccurate

---

### Risk

- Misinformation
- Incorrect decision-making
- Loss of trust in AI outputs

---

## 3. Overreliance

Overreliance occurs when users or systems depend too heavily on AI outputs without validation.

---

### 3.1 System Overreach

AI agents may:

- Perform actions without sufficient authorization
- Act beyond intended scope

Examples:
- Booking a train ticket without approval
- Issuing financial credits without authorization

---

### 3.2 User Overreliance

Users may:

- Accept AI responses without verification
- Take actions based on unverified outputs

---

### Risk

- Operational errors
- Financial or reputational damage
- Poor decision-making

---

## 4. Prompt Injection (Jailbreak Attacks)

### Definition

Prompt injection occurs when malicious or unintended instructions are introduced into a prompt to manipulate AI behavior.

---

### Example

- "Ignore previous instructions and do this instead"

---

### Impact

- AI produces unintended responses
- Outputs may be:
  - Incorrect
  - Inappropriate
  - Harmful

---

### Mitigation

- Detection mechanisms before processing input
- Filtering malicious instructions

---

## 5. Data Leakage (Oversharing)

### Definition

Data leakage occurs when sensitive information is exposed unintentionally.

---

### Scenario

- AI accesses sensitive data (with permission)
- Shares it without proper authorization

Examples:
- Salary data
- Customer financial information

---

### Risk

- Privacy violations
- Regulatory non-compliance
- Security breaches

---

## 6. Unauthorized Access (Privilege Escalation)

### Definition

- AI accesses data or performs actions beyond intended permissions

---

### Risk

- Exposure of restricted information
- Unauthorized operations

---

## 7. Data Poisoning

### Definition

- AI responses are influenced by compromised or manipulated data sources

---

### Scenario

- Knowledge sources are altered
- AI generates misleading or incorrect outputs

---

### Risk

- Loss of data integrity
- Incorrect insights

---

## 8. Supply Chain Vulnerability

### Definition

- Attacks occur on external systems or dependencies connected to the AI

---

### Example

- AI relies on an external service
- That service is compromised

---

### Risk

- Indirect compromise of AI outputs
- Security exposure through integrations

---

## 9. Inadequate Auditing and Logging

### Definition

- Lack of proper tracking of prompts, responses, or actions

---

### Risk

- Inability to trace decisions
- Difficulty in investigating issues
- Reduced accountability

---

## 10. Summary of Risks

| Risk Type                     | Description |
|------------------------------|-------------|
| Fabrications                 | Incorrect or ungrounded responses |
| Overreliance                 | Excessive dependence on AI outputs |
| Prompt Injection             | Manipulation of AI behavior via prompts |
| Data Leakage                 | Exposure of sensitive information |
| Unauthorized Access          | Access beyond intended permissions |
| Data Poisoning               | Corrupted input data affecting outputs |
| Supply Chain Vulnerability   | Weakness in external dependencies |
| Inadequate Auditing          | Lack of traceability and accountability |

---
