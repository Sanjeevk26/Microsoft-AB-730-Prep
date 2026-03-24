# Referencing Resources in Microsoft 365 Copilot Prompts

## 1. Overview

Microsoft 365 Copilot allows users to reference organizational and external resources within prompts. These resources can include:

- Emails
- Documents
- Microsoft Teams chats and meetings
- Web pages

Referencing resources improves response accuracy by grounding outputs in relevant data.

---

## 2. Permissions Requirement

To use organizational data:

- Users must have at least read access in:
  - SharePoint
  - OneDrive for Business

Copilot only accesses data the user is authorized to view.

---

## 3. Why Reference Resources

Adding resources to prompts helps:

- Improve response accuracy
- Align responses with company terminology
- Provide context-specific insights
- Enable Copilot to generate more relevant outputs

Example:
Copilot may adapt terminology (e.g., "organization" instead of "company") based on internal data.

---

## 4. Methods to Add Resources

### 4.1 Using the Plus Button

Users can:

- Add work content
- Upload images and files
- Attach cloud files

---

### 4.2 Using Slash Commands

Typing `/` allows access to:

- People
- Files
- Meetings
- Emails
- Chats
- Channels
- Sites

This enables quick insertion of relevant content into prompts.

---

## 5. Work Tab vs Web Tab

- Work tab:
  - Available with Copilot Business/Enterprise license
  - Searches organizational data

- Web tab:
  - Uses only web data and uploaded files

---

## 6. Supported File Types

Users can upload up to:

- 20 files per prompt
- Maximum size: 50 MB per file

### Supported formats:

**Documents:**
- PDF
- DOCX
- XLSX
- PPTX

**Images:**
- PNG
- JPEG
- PJP
- JFIF

**Text and Markup:**
- TXT
- JSON
- CSV
- Markdown (MD)

---

## 7. Example: Using Uploaded Files

### Scenario

A file contains:
"AB 820 exam is called Copilot for business users"

### Prompt

"What is the AB 820 exam called?"

### Result

Copilot uses the uploaded file and returns:
"Copilot for business users"

---

## 8. Referencing OneDrive Files

If a file is stored in OneDrive:

- It may not be immediately indexed by Copilot
- Manual selection may be required using "Add work content"

Example:

"Using the selected file, tell me what the AB 830 exam is called"

---

## 9. Indexing and Caching Behavior

### 9.1 Indexing Delay

- Newly uploaded files may not be immediately searchable
- Manual selection ensures correct referencing

---

### 9.2 Cached Responses

- Copilot may use cached versions of files
- Recent updates may not be reflected immediately
- Starting a new conversation may retrieve updated content

---

## 10. Document Size Recommendations

- Maximum reference size:
  - 1.5 million words or ~300 pages

- Best performance:
  - Documents under 3000 words for rewriting tasks

### Recommendation:

- Break large documents into smaller sections
- Use summarization for large files

---

## 11. Working with Updated Files

### Local File Changes

- Changes made locally are not reflected automatically
- Copilot uses previously uploaded versions

---

### OneDrive File Changes

- Updates may take time to reflect
- Cached versions may be used temporarily
- New chats are more likely to reflect updated content

---

## 12. Best Practices

- Attach relevant files explicitly when accuracy is critical
- Use smaller, focused documents
- Verify indexing before relying on files
- Use new conversations to refresh data context
- Combine prompts with clear instructions

---

## 13. Key Takeaways

- Copilot can reference multiple resource types within prompts
- Access is governed by user permissions
- File uploads and OneDrive integration enhance grounding
- Indexing and caching may affect real-time accuracy
- Proper document management improves results

---
