# Advanced Prompting Techniques in Microsoft 365 Copilot

## 1. Overview

In addition to using goal, context, expectations, and source, there are several advanced techniques that improve prompt effectiveness in Microsoft 365 Copilot.

These techniques help in:
- Clarifying instructions
- Improving output quality
- Structuring responses
- Handling ambiguity

---

## 2. Common Use Cases for Prompts

Copilot can be used for:

- Summarizing emails or meetings  
  Example:  
  "Summarize emails received in the last 7 days that are marked urgent or unanswered"

- Asking questions and generating insights

- Requesting ideas or recommendations

- Rewriting or enhancing documents

- Creating outputs such as:
  - Presentations
  - Documents
  - Excel workbooks

---

## 3. Using Separators to Avoid Ambiguity

When prompts contain both instructions and content, Copilot may misinterpret what needs to be processed.

### Problem Example

Translate the following into French:  
How do you go to the cinema? Please just give me the translation and nothing else.

Issue:
Copilot may not distinguish between:
- The content to translate
- The instruction

---

### Solution: Use Separators

Example:

Translate the following into French:

###
How do you go to the cinema?
###

Or more explicitly:

Translate everything between the hashes into French:

###
How do you go to the cinema?
###

This ensures Copilot clearly identifies the content to process.

---

## 4. Chain of Thought Prompting

Some questions are subjective or require reasoning.

### Example

Who is the best pole vaulter of all time?

This is ambiguous because "best" can mean:
- Highest jump
- Consistency
- Achievements

---

### Improved Prompt

Who is the best pole vaulter of all time?  
Take a step-by-step approach in your response.  
Cite sources and provide reasoning before giving the final answer.  
Start your final answer with "Answer is".

---

### Benefit

- Forces structured reasoning
- Improves transparency
- Produces more reliable answers

---

## 5. Structuring Output Format

Copilot may return answers in unstructured narrative form unless instructed otherwise.

### Example

Who are the best five pole vaulters of all time?

---

### Improved Prompt with Format

Who are the best five pole vaulters of all time?  
Use the following format:

- Name (Highest jump, Nationality)

---

### Benefit

- Ensures consistent output
- Improves readability
- Makes results easier to use

---

## 6. Instruction Priority

When multiple instructions are included:

- Later instructions may take priority over earlier ones

### Recommendation

- Place critical instructions toward the end of the prompt
- Keep instructions clear and structured

---

## 7. Using Prompt Examples and Gallery

Copilot provides built-in assistance for prompt creation:

- Example prompts available in new chat screen
- "See More" option for additional ideas
- Prompt Gallery:
  - Filter by task
  - Filter by job type
  - Filter by agent

---

## 8. Asking Copilot to Improve Prompts

You can directly ask Copilot to refine your prompt.

### Example

How can I improve this prompt:  
"Who are the best five pole vaulters in the world?"

Copilot may suggest:
- Defining "best"
- Adding constraints
- Specifying format

---

## 9. Asking for Clarifying Questions

Instead of assuming inputs, Copilot can ask follow-up questions.

### Example

Where is the best place to go on holiday in April?  
Please ask any clarifying questions.

---

### Typical Clarifications

- Preferred climate
- Type of holiday (beach, city, adventure)
- Travel distance
- Budget
- Interests

---

### Alternative

If clarification is not needed:

"Provide the best possible answer without asking questions"

---

## 10. Key Techniques Summary

Effective prompting can be enhanced by:

- Using separators to distinguish instructions from content
- Applying chain-of-thought prompting for reasoning tasks
- Structuring output formats explicitly
- Managing instruction order and priority
- Using prompt gallery for inspiration
- Asking Copilot to refine prompts
- Requesting clarifying questions when needed

---
