# Chapter 3: Artificial Intelligence

**Lecture 0 — Scratch**  
**Course:** CS50x 2026 | Harvard University

---

## 📝 Handnotes

**Artificial Intelligence (AI)** acts as a powerful **copilot** in most computer-related tasks.

However, the role of humans remains critically important when it comes to making **critical decisions**.

This is precisely why basic **Computer Science (CS)** skills are now more important and valuable than ever before.

---

## 💻 Code Examples

### Example 1: Basic AI Query

Getting an answer to a specific question from AI.

```python
from openai import OpenAI

client = OpenAI()

response = client.responses.create(
    input="In one sentence, what is CS50?",
    model="gpt-5"
)

print(response.output_text)
```

---

### Example 2: AI Query with User Input

Taking user input and querying the AI with it.

```python
from openai import OpenAI

client = OpenAI()

prompt = input("Prompt: ")

response = client.responses.create(
    input=prompt,
    model="gpt-5"
)

print(response.output_text)
```

---

### Example 3: Adding a System Prompt

Using a **system prompt** to control AI behavior.

```python
from openai import OpenAI

client = OpenAI()

user_prompt = input("Prompt: ")
system_prompt = "Limit your answer to one sentence. Pretend you're a cat."

response = client.responses.create(
    input=user_prompt,
    instructions=system_prompt,
    model="gpt-5"
)

print(response.output_text)
```

> **💡 Note:** The `instructions` parameter is used to assign a specific role or behavior to the AI. This is called a **System Prompt**.

---

## 🔑 Key Takeaways

- ✅ AI is a **tool**, not a replacement for humans
- ✅ Critical thinking and decision-making remain human responsibilities
- ✅ CS skills have become even more **valuable** in the age of AI
- ✅ `input` = the user's question
- ✅ `instructions` = controls AI behavior (System Prompt)
- ✅ `model` = specifies which AI model to use

---

*CS50x 2026 — Lecture 0 | Chapter 3*
