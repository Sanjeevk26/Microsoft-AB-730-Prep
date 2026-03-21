# Microsoft AB-730 Preparation  
## Introduction to Microsoft Copilot and Licensing

---

## 1. Overview

Microsoft Copilot is an AI-powered assistant integrated across Microsoft products. It enables users to:

- Generate content
- Automate workflows
- Analyze data
- Interact with enterprise information

Copilot operates based on:
- Prompts (user input)
- Grounding (data sources used for responses)
- AI-generated outputs

---

## 2. Types of Microsoft Copilot

There are three primary types relevant for AB-730:

---

### 2.1 Microsoft Copilot (Consumer / Individual)

This is the general-purpose Copilot available for personal use.

**Availability:**
- Web (copilot.microsoft.com)
- Windows
- Edge browser

**Data grounding:**
- Web data
- Files explicitly uploaded
- Limited context from the current file

**Key characteristics:**
- Does not access organizational data
- Can be used without a Microsoft 365 enterprise license
- Suitable for general productivity tasks

---

### 2.2 Microsoft 365 Copilot (Business / Enterprise)

This is the most important version for the AB-730 exam.

**Integration:**
- Word
- Excel
- PowerPoint
- Outlook
- Teams

**Data grounding:**
- Web data
- Attached files
- Current document context
- Organizational data (SharePoint, OneDrive, Teams, Outlook)

**Key capability:**
This version connects AI with enterprise data, enabling context-aware responses across business content.

**Licensing:**
- Requires a base Microsoft 365 license
- Sold as an add-on

Pricing (approximate):
- Business: $21 per user per month
- Enterprise: $30 per user per month

Important:
Copilot is not included by default in business or enterprise Microsoft 365 plans and must be purchased separately. :contentReference[oaicite:0]{index=0}

---

### 2.3 Microsoft 365 Copilot Chat

This is a web-based chat interface for Copilot.

**Without Copilot license:**
- Grounded in web data
- Grounded in uploaded files
- No access to enterprise data

**With Copilot license:**
- Grounded in web data
- Grounded in uploaded files
- Grounded in enterprise data (SharePoint, OneDrive, etc.)

**Key distinction:**
- Not embedded in Office apps
- Accessed through a browser interface

---

## 3. Microsoft 365 Plans and Copilot Availability

---

### 3.1 Individual Plans

Examples:
- Microsoft 365 Personal
- Microsoft 365 Family
- Microsoft 365 Premium

Notes:
- Include limited Copilot capabilities
- Not relevant for AB-730 exam focus

---

### 3.2 Business Plans (Up to 300 users)

| Plan                     | Desktop Apps | Copilot Included |
|--------------------------|-------------|------------------|
| Business Basic           | No          | No               |
| Business Standard        | Yes         | No               |
| Business Premium         | Yes         | No               |

Conclusion:
All business plans require a separate Copilot add-on.

---

### 3.3 Enterprise Plans (300+ users)

| Plan | Copilot Included |
|------|------------------|
| E3   | No               |
| E5   | No               |

Conclusion:
Enterprise customers must also purchase Copilot as an add-on.

---

## 4. Key Differences

| Feature                         | Microsoft Copilot | Microsoft 365 Copilot | Copilot Chat |
|--------------------------------|-------------------|------------------------|--------------|
| Web data grounding             | Yes               | Yes                    | Yes          |
| Attached file grounding        | Yes               | Yes                    | Yes          |
| Current file context           | Limited           | Yes                    | No           |
| Enterprise data (SharePoint, etc.) | No            | Yes                    | Yes (licensed only) |
| Integration with Office apps   | No                | Yes                    | No           |
| Requires add-on license        | No                | Yes                    | Partial      |

---

## 5. Core Concepts for AB-730

---

### 5.1 Grounding

Grounding determines the data sources used by Copilot:

- Web grounding: Public internet data
- Work grounding: Organizational data (SharePoint, OneDrive, Teams, Outlook)

Work grounding is critical for enterprise scenarios.

---

### 5.2 Add-on Licensing Model

Copilot follows a layered licensing model:

Base Microsoft 365 License + Copilot Add-on

This applies to both:
- Business plans
- Enterprise plans

---

### 5.3 Data Sources

Microsoft 365 Copilot uses:

- SharePoint
- OneDrive
- Microsoft Teams
- Outlook
- Microsoft Graph

These sources enable contextual and personalized responses.

---

### 5.4 Copilot vs Copilot Chat

| Aspect        | Copilot in Apps        | Copilot Chat        |
|---------------|------------------------|---------------------|
| Location      | Inside Office apps     | Web interface       |
| Context       | Current file + work data | Limited (depends on license) |
| Use case      | Productivity workflows | General queries     |

---

## 6. Practical Scenario

**User request:**
"Summarize last quarter sales performance"

**Behavior comparison:**

- Microsoft Copilot:
  Uses general web knowledge, cannot access company data

- Copilot Chat (no license):
  Cannot access internal data, limited usefulness

- Microsoft 365 Copilot:
  Pulls data from:
  - Excel files
  - SharePoint documents
  - Emails
  - Teams conversations

Provides a contextual and accurate summary

---

## 7. Key Takeaways

- Microsoft Copilot is a general AI assistant
- Microsoft 365 Copilot is enterprise-focused and exam-critical
- Copilot requires an additional license in business and enterprise environments
- Work data grounding is the most important differentiator
- Copilot Chat is a separate web-based interface with limited capabilities without licensing

---

## 8. Suggested Next Topics for AB-730

To continue preparation, focus on:

- Copilot Studio
- Agents and agent orchestration
- Topics vs triggers
- Event-driven automation
- Security and compliance (Microsoft Purview)
- Data governance and access control
- Microsoft Graph integration

---
