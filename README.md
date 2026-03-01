# Agent-Architect-Notes

This repository serves as a personal knowledge base for my journey into becoming an **Agent Architect**. The core philosophy of this study is that Large Language Models (LLMs) are not just chatbots, but the **kernels of a new type of operating system**.

---

## 🧠 Fundamental Understandings

### 1. The Nature of the Model
* **The Two Files**: At its physical core, an LLM consists of just two files: a **parameter file** (the neural network weights) and a **run file** (the code to execute the model).
* **Lossy Compression**: Training an LLM is essentially a lossy compression of the internet.
* **Next-Word Prediction**: The model’s only job is to predict the next word in a sequence based on a probability distribution.
* **Hallucination**: Since the compression is lossy, the model often "dreams" or fills in gaps with plausible but incorrect data when it lacks specific details.

### 2. The Evolution of Intelligence
* **Pre-training**: This stage involves learning world knowledge from massive datasets.
* **Fine-tuning (SFT)**: This aligns the model's behavior to act as a helpful assistant rather than just a document generator.
* **RLHF**: Reinforcement Learning from Human Feedback helps the model learn what constitutes a "good" or "preferred" response.

---

## 🛠️ The Agent Paradigm: LLM as an OS

The architecture of an Agent can be viewed through the lens of a computer operating system:

* **CPU**: The LLM serves as the central processing unit, handling reasoning and logic.
* **RAM (Memory)**: The **Context Window** acts as the working memory, which is limited and must be managed carefully.
* **Peripherals (Tools)**: These include search engines, calculators, code interpreters, and APIs that provide the Agent with external capabilities.
* **The Formula**: **Agent = LLM + Tools**.

---

## 🚀 Advanced Reasoning & Safety

### System 1 vs. System 2 Thinking
* **System 1**: Fast, intuitive, and automatic responses.
* **System 2**: Slow, deliberate, and deep thinking; this is the future of Agent reasoning where models "think" before they speak to reduce errors.

### Security Mindset
* **Prompt Injection**: External data (like a webpage the Agent reads) can contain hidden commands that hijack the Agent's instructions.
* **Jailbreaking**: Using roleplay or encoding to bypass the model's safety guardrails.
* **Verification**: Never fully trust the model's output; always implement validation steps, especially for critical tasks like code execution or database queries.

---

## 📖 Reference
* Andrej Karpathy: *"Intro to Large Language Models"*
* Agent Architect Bootcamp Series
