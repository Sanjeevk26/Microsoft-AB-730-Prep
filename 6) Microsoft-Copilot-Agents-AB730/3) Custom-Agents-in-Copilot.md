# Creating a Custom Agent Using the Configure Tab (Microsoft 365 Copilot)

## 1. Overview

This guide explains how to create a custom agent in Microsoft 365 Copilot using the **Configure tab** without relying on templates.

The Configure tab allows full control over:
- Agent identity
- Instructions and behavior
- Knowledge sources
- Capabilities
- Suggested prompts

---

## 2. Steps to Create an Agent

1. Click **Create Agent**
2. Navigate to the **Configure tab**
3. Do not select a template
4. Configure the agent manually

---

## 3. Agent Configuration Sections

---

### 3.1 Name and Icon

- Provide a meaningful name for the agent  
  Example: *Corporate Entertainment Policy Assistant*

- Optional:
  - Upload a custom icon (PNG, 192 × 192 px)
  - Add background color for transparent icons

---

### 3.2 Description

- Maximum length: **1000 characters**
- Purpose: Explain what the agent does

#### Example

"This agent helps determine whether proposed expenses comply with the corporate entertainment policy."

---

### 3.3 Instructions

- Maximum length: **8000 characters**
- Defines how the agent should behave

#### Example Instructions

- Use the attached document to answer questions about the corporate entertainment policy  
- If unsure, respond:  
  "I’m sorry, I don’t know the answer to this question. Please contact Human Resources."  
- Do not answer questions outside the scope of the policy  

---

## 4. Knowledge Sources

Knowledge grounding allows the agent to provide accurate, context-based responses.

---

### 4.1 Limits

- Up to **20 knowledge sources**
- Up to **4 public web links**

---

### 4.2 Web Sources

- Maximum depth: **2 levels**
  - Allowed: `/level1/level2`
  - Not allowed: `/level1/level2/level3`

- Option:
  - Restrict responses to specified websites only

---

### 4.3 SharePoint Sources

Supports:

- Files
- Folders
- Entire sites

#### File Types Supported

- Word: `.doc`, `.docx`
- PowerPoint: `.ppt`, `.pptx`
- Excel: `.xls`, `.xlsx`
- PDF
- Text files
- HTML files

---

### 4.4 File Limits

- SharePoint files:
  - Up to **100 files**
  - Max size: **512 MB**
- Excel workbooks:
  - Max size: **30 MB**

---

### 4.5 Permissions

- SharePoint permissions and sensitivity labels are respected
- Only accessible data is used

---

### 4.6 Additional Sources

You can also include:

- Microsoft Teams:
  - Chats
  - Meetings
- Outlook:
  - Emails (entire inbox or selected)
- Organizational profile and chart data

---

### 4.7 Uploading Files

- Upload up to **20 files from device**

Supported formats:
- Word
- PDF
- PowerPoint
- Text
- Excel

Note:
- Markdown (`.md`) files are not supported

---

## 5. Capabilities

Capabilities extend what the agent can do.

---

### 5.1 Code Interpreter

Despite the name, it can:

- Analyze data
- Generate charts
- Create documents:
  - Word
  - Excel
  - PowerPoint
- Plot mathematical equations
- Generate code snippets

---

### 5.2 Image Generator

- Create images and artwork based on prompts

---

## 6. Suggested Prompts

- Up to **6 prompts**
- Helps users start conversations

---

### Example Suggested Prompts

- "Is music allowed?"
- "Is theatre allowed?"
- "Can I attend local festivals?"
- "Am I allowed to consume alcohol during company events?"
- "What expenses are eligible for reimbursement?"
- "What happens if I breach this policy?"

---

## 7. Example Agent Configuration

### Name

Corporate Entertainment Policy Assistant

---

### Description

Helps determine whether expenses or activities comply with the corporate entertainment policy.

---

### Instructions

- Use attached policy documents
- Stay within policy scope
- Redirect unknown queries to HR

---

### Knowledge

- Uploaded policy document (Word file)
- Optional SharePoint or web sources

---

### Capabilities

- Code Interpreter enabled

---

### Suggested Prompts

- Policy-related queries for quick access

---

## 8. Best Practices

- Keep instructions clear and restrictive
- Use trusted and relevant knowledge sources
- Limit scope to avoid incorrect answers
- Enable only required capabilities
- Provide useful suggested prompts for users

---
