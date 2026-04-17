# 🔗 LangChain Sequential Practice

This repository contains a Jupyter Notebook demonstrating **Sequential Chains in LangChain**.

---

## 📌 About

This project focuses on how to use **Sequential Chains** to connect multiple LLM steps together.

Instead of a single prompt → response, the output of one step is passed as input to the next step, creating a **multi-step workflow**.

Sequential chains help build more advanced AI pipelines compared to one-shot prompts ([Richhiey Thomas][1])

---

## 🧠 What is Sequential Chain?

A Sequential Chain in LangChain:

* Takes input from the user
* Passes it through multiple LLM steps
* Each step processes and improves the result
* Produces a final structured output

👉 Example flow:

```
Input → Step 1 (Generate content)
      → Step 2 (Refine / Transform)
      → Step 3 (Final Output)
```

---

## 🚀 Features

* Implementation of Sequential Chains
* Multi-step LLM processing
* Prompt templates usage
* Demonstrates chaining outputs between steps

---

## 📓 Notebook Content

The notebook includes:

* Importing LangChain modules
* Creating prompt templates
* Building LLM chains
* Combining multiple chains sequentially
* Running end-to-end workflow

---

## ⚙️ Setup

1. Clone the repository:

```bash
git clone https://github.com/amjathhussain31/LangChain-Practice.git
cd LangChain-Practice
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
jupyter notebook
```

---

## ▶️ Usage

Run the notebook cells step by step to see how:

* Input is processed
* Each chain contributes to the final result
* Outputs flow between steps

---

## 🛠️ Tech Used

* Python
* LangChain
* Jupyter Notebook
* LLM APIs (Ollama)

---

