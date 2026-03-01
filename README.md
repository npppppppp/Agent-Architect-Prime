# Agent-Architect-Notes

[English Version](#english-version) | [中文版](#chinese-version)

---

<a name="english-version"></a>
## English Version

This repository serves as a personal knowledge base for my journey into becoming an **Agent Architect**. The core philosophy of this study is that Large Language Models (LLMs) are not just chatbots, but the **kernels of a new type of operating system**.

### 🧠 Fundamental Understandings
* **The Nature of the Model**: At its physical core, an LLM consists of just two files: a **parameter file** (the neural network weights) and a **run file** (the code to execute the model).
* **Lossy Compression**: Training an LLM is essentially a lossy compression of the internet.
* **Next-Word Prediction**: The model’s only job is to predict the next word in a sequence based on a probability distribution.
* **Hallucination**: Since the compression is lossy, the model often "dreams" or fills in gaps with plausible but incorrect data when it lacks specific details.

### 🛠️ The Agent Paradigm: LLM as an OS
The architecture of an Agent can be viewed through the lens of a computer operating system:
* **CPU**: The LLM serves as the central processing unit, handling reasoning and logic.
* **RAM (Memory)**: The **Context Window** acts as the working memory, which is limited and must be managed carefully.
* **Peripherals (Tools)**: These include search engines, calculators, code interpreters, and APIs that provide the Agent with external capabilities.
* **The Formula**: **Agent = LLM + Tools**.

### 🚀 Advanced Reasoning & Safety
* **System 1 vs. System 2 Thinking**: System 1 represents fast, intuitive responses, while System 2 involves slow, deliberate, and deep thinking; this is the future of Agent reasoning.
* **Security Mindset**: Be aware of **Prompt Injection** (malicious hidden commands) and **Jailbreaking** (bypassing safety guardrails).
* **Verification**: Never fully trust the model's output; always implement validation steps for critical tasks.

---

<a name="chinese-version"></a>
## 中文版

本仓库是我成为 **Agent 架构师** 进阶之路的个人知识库。其核心理念是将大语言模型（LLM）视为一种**新型操作系统的内核**。

### 🧠 核心认知
* **模型的本质**：在物理层面，大模型仅由两个文件组成：**参数文件**（神经网络权重）和**运行代码**（执行前向传播的代码）。
* **有损压缩**：训练大模型本质上是对互联网海量信息进行的一种有损压缩。
* **预测下一个词**：模型的核心任务是基于概率分布预测序列中的下一个词。
* **幻觉现象**：由于压缩是有损的，当缺乏具体细节时，模型会基于概率进行“脑补”，生成看似合理但错误的内容。

### 🛠️ Agent 范式：LLM 即操作系统
我们可以通过计算机操作系统的视角来理解 Agent 架构：
* **CPU**：LLM 作为中央处理器，负责逻辑推理。
* **内存 (RAM)**：**上下文窗口**（Context Window）充当工作记忆，其容量有限，需精细管理。
* **外设（工具）**：包括搜索引擎、计算器、代码解释器和各类 API，为 Agent 提供外部执行能力。
* **核心公式**：**Agent = LLM (大脑) + Tools (工具)**。

### 🚀 深度推理与安全
* **系统 1 与系统 2 思维**：系统 1 代表快速、直觉式的反应；系统 2 代表慢速、理性且深度的思考。让模型具备“慢思考”能力是 Agent 推理的进化方向。
* **安全意识**：需警惕**提示词注入**（恶意隐藏指令劫持）和**越狱攻击**（绕过模型安全限制）。
* **结果校验**：永远不要完全信任模型的输出；在执行关键任务（如数据库查询）前必须建立校验环节。

---

## 📖 Reference
* Andrej Karpathy: *"Intro to Large Language Models"*
* Agent Architect Bootcamp Series
