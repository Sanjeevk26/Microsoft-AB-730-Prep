# Microsoft 365 Copilot Memory and Custom Instructions

## 1. Overview

Microsoft 365 Copilot uses:

- Memory: Stores factual information about the user
- Custom Instructions: Defines how responses should be generated

These features improve personalization and response relevance.

---

## 2. Copilot Memory

### 2.1 What is Memory

Memory allows Copilot to remember user-specific facts across conversations.

Examples:
- Location
- Preferences
- Repeated contextual inputs

---

### 2.2 Example

Prompt:
"Remember that I live in New York"

Result:
- Copilot stores this information
- A "Memory updated" notification appears

---

### 2.3 Usage of Memory

In a new chat:

Prompt:
"What is happening in theaters near where I live?"

Result:
- Copilot uses stored memory (e.g., New York)
- Even if previous location was different

---

### 2.4 Automatic Memory Updates

- Copilot may store information automatically
- Users should monitor for:
  - "Memory updated" notifications

---

## 3. Temporary Chat and Memory

### 3.1 Temporary Chat Behavior

- Does not store memory
- Does not use existing memory
- Not saved in chat history

---

### 3.2 Example

Prompt in temporary chat:
"Remember that I live in Paris"

Result:
- No memory is stored
- Used only for current session

---

## 4. Managing Memory

### 4.1 Access Memory Settings

1. Click **three dots (ellipsis)** in top-right corner
2. Go to **Settings**
3. Select **Personalization**

---

### 4.2 Memory Options

- View stored memory (e.g., "User lives in New York")
- Delete specific memory entries
- Disable memory entirely

---

### 4.3 Disabling Memory

- Prevents Copilot from storing new memories
- Applies to both:
  - User-defined memory
  - Automatically detected memory

---

## 5. Custom Instructions

### 5.1 What are Custom Instructions

Custom instructions define how Copilot should respond.

They control:

- Tone
- Format
- Level of detail
- Output preferences

---

### 5.2 Example Instructions

- Use a casual tone
- Provide temperatures in Kelvin
- End responses with a disclaimer

---

### 5.3 Behavior

- Applied across all new chats
- Overrides default response style
- Can be enabled or disabled

---

## 6. Example Behavior with Instructions

Prompt:
"What is the weather near where I live?"

Result:
- Uses default or inferred location
- Applies custom instructions:
  - Temperature in Kelvin
  - Custom tone
  - Includes defined closing statement

---

## 7. Memory vs Custom Instructions

| Feature              | Memory                          | Custom Instructions              |
|----------------------|----------------------------------|----------------------------------|
| Purpose              | Store factual user data         | Control response behavior        |
| Example              | "User lives in New York"        | "Use casual tone"                |
| Scope                | Context for answers             | Style and format of answers      |
| Persistence          | Stored across conversations     | Applied globally to responses    |

---

## 8. Best Practices

- Use memory for stable facts (e.g., location)
- Use custom instructions for response preferences
- Monitor memory updates carefully
- Use temporary chat for privacy-sensitive queries
- Periodically review and clean stored memory

---

