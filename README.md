# LLM-Powered EDA Tool 🧠📊

A powerful AI-driven EDA application built with **Gradio**, **Pandas**, and **Seaborn**, enhanced by **LLM-powered insights using Ollama's Mistral-7B**.

This tool allows you to upload a CSV file and automatically:
- Clean and summarize the data
- Generate visualizations (histograms, bar plots, correlation heatmaps, etc.)
- Ask natural language questions about the dataset and get insights powered by an LLM

---

## 🚀 Features

- 📂 **Upload CSV files** via a simple web interface  
- 🔍 **Automatic EDA**:
  - Missing value summary
  - Descriptive statistics
  - Data type overview
- 📊 **Visualizations**:
  - Distribution plots
  - Correlation heatmap
  - Categorical vs numerical analysis
- 🤖 **LLM-Powered Insights**:
  - Ask questions like:
    - *"Which feature impacts sales the most?"*
    - *"Are there any outliers in the data?"*
  - LLM (Mistral-7B via Ollama) generates human-readable insights
- 🌐 **Gradio UI** for interactive usage
- 🧩 Built with a modular and extensible Python codebase

---

## 🧱 Tech Stack

- **Language**: Python  
- **Libraries**:  
  - `pandas`, `numpy`  
  - `matplotlib`, `seaborn`  
  - `gradio`  
- **LLM Backend**: [Ollama](https://ollama.ai/) with **Mistral-7B**

---
![logo](https://github.com/Shashank-Sen/LLM-Powered-EDA-Tool-/blob/main/EDA%20TOOL/data_visuals/Education_distribution.png)
---
![logo](https://github.com/Shashank-Sen/LLM-Powered-EDA-Tool-/blob/main/EDA%20TOOL/data_visuals/DailyRate_distribution.png)

---

## ⚙️ Prerequisites

Before running the project, make sure you have:

- **Python 3.9+** installed  
- **pip** (Python package manager)  
- **Ollama** installed and running locally  
- **Mistral model** pulled in Ollama:

```bash
ollama pull mistral
