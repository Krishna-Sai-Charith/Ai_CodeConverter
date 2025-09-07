# ⚡ Code Translator & Benchmarking with AI + Gradio UI

Welcome to the **AI-powered Code Translator & Performance Comparator** project! 🚀 This tool helps you **convert Python code into high-performance C, C++, or Rust** using **AI models** like GPT-4o, Claude, and Hugging Face models — and benchmark execution speeds to analyze how different languages perform.

---

## 🧠 Project Overview

This project allows users to:
- 🔁 **Convert code** from **Python to C / C++ / Rust** using advanced AI models.
- 🧪 **Run the original and converted code** to measure **execution time**.
- 📊 **Compare performance** between languages for the same logic.
- 🖥️ Use a beautiful **Gradio-based web interface** to interact with the system.

This project not only explores **code translation** but also **benchmarks execution efficiency** across programming languages.

---

## 💡 Why This Project Matters

In the real world:
- Different programming languages have different **runtime performances**.
- AI-assisted tools can help **automate cross-language development**.
- Developers can make better choices about language selection based on **actual performance data**.

This project provides a **hands-on learning platform** to explore all these aspects interactively.

---

## 🎯 What I Learned

✅ Through this project, I learned:
- How to integrate **multiple AI model APIs** (OpenAI, Claude, Hugging Face).
- How to build a **real-time UI** using **Gradio**.
- Working with **code compilation and execution pipelines** in Python.
- Understanding the performance tradeoffs between **Python, C++, C, and Rust**.
- Managing **system-specific dependencies** like compilers and runtimes.

---

## ⚙️ Prerequisites

Make sure you have the following installed and configured before running the project:

### 🔐 API Keys (set via environment variables or directly)
- **OpenAI API Key** – for models like `gpt-4o`
- **Anthropic API Key** – for Claude models
- **Hugging Face Token** – for CodeQwen or Starcoder

> 💡 You can use `.env` file or manually set them in your script

```env
OPENAI_API_KEY=your-openai-key
ANTHROPIC_API_KEY=your-anthropic-key
HF_TOKEN=your-huggingface-token
