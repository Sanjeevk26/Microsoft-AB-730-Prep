# Testing and Sharing a Custom Agent in Microsoft 365 Copilot

## 1. Overview

After creating a custom agent, the next steps are:

- Testing the agent
- Creating (publishing) the agent
- Sharing it with others
- Using it within chats

This ensures the agent works as expected and can be reused across the organization.

---

## 2. Testing the Agent

Before creating (publishing) the agent, you can test it in draft mode.

---

### Example Tests

- "Am I allowed to drink alcohol while on company time?"
- "What expenses are eligible for reimbursement?"

---

### Observations

- Responses are **fast** because:
  - The agent uses limited, specific knowledge sources
  - It does not search the entire web

- This makes agents highly efficient for:
  - Policy-based queries
  - Domain-specific tasks

---

### New Chat Option

- Click **New Chat** to reset the conversation
- Allows testing multiple independent queries

---

## 3. Draft vs Created Agent

### Draft Mode

- Agent shows: **"Draft auto-saved"**
- Not yet available for others
- Only visible to the creator

---

### Creating the Agent

1. Click **Create**
2. Wait for processing (few seconds)
3. Agent becomes active

---

## 4. Managing the Agent

After creation, you can:

- Edit the agent
- Share the agent
- Uninstall the agent
- Download agent (ZIP file)

---

### Iterative Improvement

Typical workflow:

1. Create basic agent
2. Test with prompts
3. Refine instructions
4. Update agent
5. Repeat

---

## 5. Sharing the Agent

### Access Options

You can share the agent with:

- Only yourself
- Specific users or groups
- Entire organization

---

### Steps

1. Click **Share**
2. Select access level
3. Copy link
4. Click **Apply**

---

### Important Notes

- Users must have a valid Copilot license
- Shared users can:
  - Add the agent
  - Use it in their Copilot environment

---

## 6. SharePoint Permission Behavior

If the agent uses SharePoint data:

- The agent respects **user permissions**
- Each user only sees data they have access to

---

### Additional Option

- You can grant access to specific files/folders when sharing
- Cannot grant access to entire SharePoint site

---

## 7. Accessing the Shared Agent

Users can:

- Open the shared link
- Click **Add**
- Use the agent in Copilot

---

### Agent Availability

- Appears in:
  - Agent list
  - All Agents section
- Can be pinned for quick access

---

## 8. Using Agents in Chat

Agents can be used without opening them directly.

---

### Method 1: Using Plus (+)

- Click **+**
- Select **Chat with an agent**

---

### Method 2: Using @ Mention

- Type `@`
- Select the agent
- Ask your question

---

### Example

"@Corporate Entertainment Policy  
Am I allowed to listen to music while on business?"

---

## 9. Example Behavior

- Agent responds based on policy:
  - Music concerts → Not allowed
  - Private listening → Allowed

---

## 10. Best Practices

- Test thoroughly before sharing
- Use clear and restricted instructions
- Validate responses for accuracy
- Share only with relevant users
- Regularly update and refine the agent

---

## 11. Key Takeaways

- Agents should be tested in draft mode before publishing
- Creation makes the agent available for sharing
- Sharing enables reuse across the organization
- Permissions control data visibility
- Agents can be used directly within chat using @ or +

---
