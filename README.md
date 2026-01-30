🩺 Preventive Health Risk Assessment System (Agentic AI)
Overview

The Preventive Health Risk Assessment System is an Agentic AI based application designed to analyze lifestyle behaviors and promote preventive health awareness.
The system processes user provided lifestyle information, evaluates potential preventive health risk tendencies using trusted guidelines, and delivers calm, supportive, and non clinical lifestyle guidance.

This project focuses on early awareness and prevention, not diagnosis or treatment.

Key Objectives

Transform unstructured lifestyle inputs into structured summaries

Identify preventive health risk tendencies using guideline based reasoning

Provide general, supportive lifestyle improvement guidance

Maintain ethical AI constraints such as non diagnosis and non alarmist language

System Architecture

The system is built using a multi agent pipeline with clear responsibility separation.

1️⃣ Lifestyle Data Analysis Agent

Converts raw user input into structured summaries

Covers physical activity, sleep, diet, and stress

Does not provide advice or identify health conditions

2️⃣ Preventive Health Risk Detection Agent

Compares lifestyle summaries with preventive healthcare guidelines

Identifies risk tendencies linked to lifestyle behaviors

Uses retrieval augmented generation for grounded reasoning

Does not provide recommendations or diagnoses

3️⃣ Preventive Health Advisory Assistant

Provides general, non clinical lifestyle suggestions

Encourages small, achievable, and sustainable changes

Maintains a calm and supportive tone

Technologies Used

LangFlow for agent orchestration and visual flow design

IBM watsonx Granite Models for reasoning and embeddings

Chroma DB for vector storage and guideline retrieval

RAG (Retrieval Augmented Generation) using preventive healthcare guidelines

Agentic AI architecture with modular responsibilities

Features

Agent based reasoning pipeline

Structured and consistent outputs

Explainable guideline grounded risk identification

Ethical AI safeguards

Minimalist and readable user responses

Designed for real world preventive healthcare awareness

Ethical and Safety Constraints

No medical diagnosis or treatment advice

No medication or supplement recommendations

No emergency or alarmist messaging

General guidance only

Clear handling of insufficient information

Repository Contents

flow.json
LangFlow export containing the complete agentic pipeline

How to Use

Import the provided JSON file into LangFlow

Configure API keys for the selected language models

Run the flow in Playground mode

Provide lifestyle related input in natural language

Observe structured analysis, risk detection, and advisory output

Use Cases

Preventive health awareness platforms

Wellness and lifestyle monitoring tools

Educational healthcare AI demonstrations

Hackathons and academic showcases

Ethical AI in healthcare research

Disclaimer

This system is intended for educational and preventive awareness purposes only.
It does not replace professional medical consultation.
