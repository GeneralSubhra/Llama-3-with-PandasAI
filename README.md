# Llama-3-with-PandasAI

A local **AI-powered data exploration** application built using **PandasAI**, **Llama 3**, and **Ollama**.  
This project allows you to explore, clean, and analyze datasets using **natural language queries**, all while running completely on your local machine.

---

## 🚀 Overview

Data analysis doesn’t always require complex setups or cloud-based APIs.  
This repository demonstrates how to build a simple application that empowers **local data exploration** using modern Large Language Models (LLMs).

The application combines:
- **PandasAI** for natural language interaction with Pandas DataFrames
- **Llama 3** as the reasoning and language engine
- **Ollama** to run LLMs locally without relying on external services

---

## 🧠 Tech Stack

### 🔹 PandasAI
PandasAI bridges the gap between **Pandas DataFrames** and **LLMs**, enabling:
- Natural language querying
- Data cleaning
- Exploratory analysis
- Automated visualizations

### 🔹 Llama 3
Llama 3 is a powerful open-source Large Language Model from Meta, capable of:
- Question answering
- Summarization
- Code generation
- Reasoning over structured data

### 🔹 Ollama
Ollama runs LLMs locally and exposes them through a simple API, allowing applications to:
- Send prompts to models like Llama 3
- Receive responses without cloud dependency
- Maintain full data privacy

---

## ✨ Features

- 📊 Analyze CSV / tabular data using natural language
- 🧠 Local LLM inference (no API keys required)
- ⚡ Fast iteration with Streamlit UI
- 🔐 Data never leaves your machine

---

## 🛠️ Requirements

- Python 3.8+
- Ollama installed locally
- Llama 3 model pulled in Ollama
- Basic familiarity with Pandas

---

## 📦 Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/GeneralSubhra/Llama-3-with-PandasAI.git
cd Llama-3-with-PandasAI
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate   # Linux / macOS
venv\Scripts\activate    # Windows
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🧠 Setup Ollama & Llama 3

### Install Ollama
Follow instructions from: https://ollama.com

### Pull Llama 3 Model

```bash
ollama pull llama3
```

### Start Ollama Server

```bash
ollama serve
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

Open the Streamlit URL shown in your terminal.

---

## 💬 Example Prompts

- "Show me summary statistics of the dataset"
- "What columns have missing values?"
- "Plot the distribution of age"
- "Find correlations between numerical features"

---

## 🧩 How It Works

1. Dataset is loaded into a Pandas DataFrame
2. PandasAI connects the DataFrame to Llama 3 via Ollama
3. User enters a natural language prompt
4. LLM interprets the query and generates Pandas code
5. Results are returned as text or plots

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 🙌 Author

Built by **Subhranil Paul**  
Exploring the intersection of **LLMs, local AI, and data analysis**.
