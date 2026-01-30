# 🩺 Preventive Health Risk Assessment System  
### Agentic AI for Lifestyle Based Preventive Health Awareness

## 📌 Overview

The **Preventive Health Risk Assessment System** is an **Agentic AI based application** designed to analyze lifestyle behaviors and promote **preventive health awareness**.

The system processes **user provided lifestyle information**, evaluates **potential preventive health risk tendencies** using trusted guidelines, and delivers **calm, supportive, and non clinical lifestyle guidance**.

This project focuses on **early awareness and prevention**, not diagnosis or treatment.

---

## 🎯 Key Objectives

- Transform unstructured lifestyle inputs into structured summaries  
- Identify preventive health risk tendencies using guideline based reasoning  
- Provide general, supportive lifestyle improvement guidance  
- Maintain ethical AI constraints such as non diagnosis and non alarmist language  

---

## 🧠 System Architecture

The system is built using a **multi agent pipeline** with clear responsibility separation.

### 🔹 1. Lifestyle Data Analysis Agent
- Converts raw user input into structured lifestyle summaries  
- Covers physical activity, sleep, diet, and stress  
- Does not provide advice or identify health conditions  

### 🔹 2. Preventive Health Risk Detection Agent
- Compares lifestyle summaries with preventive healthcare guidelines  
- Identifies lifestyle related risk tendencies  
- Uses Retrieval Augmented Generation for grounded reasoning  
- Does not provide recommendations or diagnoses  

### 🔹 3. Preventive Health Advisory Assistant
- Provides general, non clinical lifestyle suggestions  
- Encourages small, achievable, and sustainable changes  
- Maintains a calm and supportive tone  

---

## 🛠️ Technologies Used

- **LangFlow** for agent orchestration and visual flow design  
- **IBM watsonx Granite Models** for reasoning and embeddings  
- **Chroma DB** for vector storage and similarity search  
- **Retrieval Augmented Generation (RAG)** using preventive healthcare guidelines  
- **Agentic AI architecture** with modular agents  

---

## ✨ Key Features

- Multi agent reasoning pipeline  
- Structured and consistent outputs  
- Explainable guideline grounded risk identification  
- Ethical AI safeguards  
- Minimalist and readable user responses  

---

## ⚖️ Ethical and Safety Constraints

- No medical diagnosis or treatment advice  
- No medication or supplement recommendations  
- No emergency or alarmist messaging  
- General guidance only  
- Explicit handling of insufficient information  

---

## 📂 Repository Contents

- `flow.json`  
  LangFlow export containing the complete agentic pipeline  

---

## 🚀 How to Use

1. Import the provided JSON file into LangFlow  
2. Configure API keys for the selected language models  
3. Run the flow in Playground mode  
4. Provide lifestyle related input in natural language  
5. Observe structured analysis, risk detection, and advisory output  

---

## 🧪 Use Cases

- Preventive health awareness platforms  
- Wellness and lifestyle monitoring tools  
- Educational healthcare AI demonstrations  
- Hackathons and academic showcases  
- Ethical AI in healthcare research  

---

## ⚠️ Disclaimer

This system is intended for **educational and preventive awareness purposes only**.  
It does not replace professional medical consultation.
