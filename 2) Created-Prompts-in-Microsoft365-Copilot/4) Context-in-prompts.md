# Context and Its Impact on Microsoft 365 Copilot Responses

## 1. Overview

Microsoft 365 Copilot uses context to generate more relevant and accurate responses. Context can come from:

- Conversation history
- Work files (SharePoint, OneDrive)
- Web data
- Current open documents

Understanding how context works is critical for effective prompting and accurate outputs.

---

## 2. Context from Conversation History

Copilot maintains context within a conversation thread.

### Example

Initial prompt:
"What is the weather today in Madrid?"

Follow-up prompt:
"What is the weather forecast for tomorrow?"

Observation:
- The second prompt does not mention Madrid
- Copilot uses prior context to infer that the location is still Madrid

### Key Point

- Copilot uses previous messages in the same conversation to infer missing details

---

## 3. Context from Work Files

Copilot can use organizational data stored in:

- SharePoint
- OneDrive

### Example

Prompt:
"Using the file about the AB 830 exam, what is the name of the exam?"

Observation:
- The file is not explicitly referenced using a command
- Copilot searches work files to locate relevant content
- Returns the correct answer based on that file

---

## 4. Role of Microsoft Graph

Microsoft Graph enables context awareness by connecting Microsoft 365 services and data.

### Data Sources Connected by Microsoft Graph

- Users and groups
- Teams and channels
- Emails and calendars (Exchange)
- OneDrive files
- SharePoint documents and lists
- Teams chats, messages, and meetings
- Tasks and organizational relationships

---

### Key Functions

- Retrieves relevant organizational data
- Enforces user permissions
- Grounds Copilot responses in enterprise data

Important:
Copilot only accesses data that the user is authorized to view.

---

## 5. Context from Web Data

Copilot can also use publicly available web information.

### Example

Prompt:
"Tell me about the AB-730 Microsoft exam"

Observation:
- Copilot generates a response using web-based information
- No internal organizational data is required

---

## 6. Context from Current Open Documents

Copilot can use the content of the currently open document in an application.

### Example

Scenario:
A document contains:
"The AB 840 exam is called Copilot for everyone"

Prompt:
"Using the current document, what is the name of the Microsoft AB 840 exam?"

Result:
- Copilot retrieves the answer from the open document

---

## 7. Types of Context in Copilot

| Context Source        | Description |
|----------------------|-------------|
| Conversation history | Previous prompts in the same chat |
| Work files           | SharePoint and OneDrive data |
| Web data             | Internet-based information |
| Current document     | Open file in application |

---

## 8. External Data via Connectors

Copilot can also incorporate data from external systems using:

- Pre-built connectors
- Custom connectors

This allows integration beyond Microsoft 365.

---

## 9. Security and Access Control

- Microsoft Graph enforces permission-based access
- Only accessible data is used in responses
- Organizational security, compliance, and privacy policies are maintained

---
