# Agentic_AI
# Multi-Agent Research & Writing System

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Google AI](https://img.shields.io/badge/API-Gemini_1.5-green)
![Platform](https://img.shields.io/badge/Platform-Google_Colab-orange)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

### 📘 Project Overview

This repository implements a **multi-agent AI system** powered by **Google Gemini** that can:

1. **Research** a topic automatically  
2. **Write** a structured educational article  
3. **Critique and improve** the article  

If no API key is available (or quota is exceeded), it switches to **Demo Mode** and still produces topic-specific content using Wikipedia summaries — ensuring the pipeline always runs end-to-end.

---

### 🧩 Agents Overview

| Agent | Function | Description |
|:------|:----------|:-------------|
| 🧠 **ResearchAgent** | Data Gathering | Searches Wikipedia and web sources for topic summaries |
| ✍️ **WriterAgent** | Article Creation | Writes structured educational content using Gemini or demo mode |
| 🔍 **CriticAgent** | Review & Editing | Generates critiques and improves clarity, tone, and structure |

---

### ⚙️ Features

✅ Works with or without a Gemini API key  
✅ Automatically switches to demo mode during quota limits  
✅ Generates topic-aware educational content dynamically  
✅ Saves all outputs (research, drafts, critiques) in `/content/outputs/`  
✅ Optimized for **Google Colab** runtime  

---

### 🚀 Getting Started

#### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/gemini-multi-agent-system.git
cd gemini-multi-agent-system
