# 🤖 EngagePro Chatbot – Streamlit & Retrieval-Based Assistant

This project is an interactive chatbot application developed as part of the **Generative AI Solutions** module.

The chatbot is designed for EngagePro, a fictional generative AI company, to provide accurate and reliable answers about the company’s products and services, while also supporting general and technical queries through live Wikipedia search.

A strong emphasis is placed on user experience, factual accuracy and ethical safeguards.

---

## 🎯 Project Objective

The goal of this project is to:

- build a user-friendly and visually engaging chatbot interface using Streamlit
- support two types of queries:
  - company-specific questions about EngagePro
  - general or technical questions using Wikipedia as an external knowledge source
- reduce hallucinations and improve response reliability
- apply ethical and responsible AI design principles

---

## 🧱 Key Features

- **Interactive Streamlit interface**
  - clean and responsive chat-based UI

- **EngagePro-aware chatbot**
  - answers questions related specifically to EngagePro, its products and services

- **Wikipedia-powered search**
  - retrieves information from Wikipedia for general and technical queries
  - reduces reliance on the language model’s internal knowledge

- **Friendly and professional conversational tone**
  - suitable for customer-facing applications

---

## 🛡️ Ethical & Reliability Safeguards

The chatbot includes measures to:

- reduce hallucinations by:
  - prioritising retrieval-based answers when external knowledge is required
  - routing suitable queries to Wikipedia search
- improve factual accuracy by:
  - grounding responses on retrieved content where possible
- support responsible AI usage by:
  - maintaining neutral and unbiased language
  - avoiding speculative or unverifiable answers

---

## 👩‍💻 My Role

This is an individual coursework project for the **Generative AI Solutions** module.

My contributions include:

- designing and implementing the Streamlit user interface
- building chatbot logic for:
  - EngagePro-specific queries
  - Wikipedia-based information retrieval
- implementing routing between internal knowledge and external search
- adding safeguards to reduce hallucination and improve response reliability

---

## 🛠️ Tech Stack

- Python
- Streamlit
- Large Language Model (LLM)
- Wikipedia API / retrieval tools

---

## 🧠 What this project demonstrates

- building a real-world chatbot application using generative AI
- integrating external knowledge sources into LLM workflows
- applying responsible AI and ethical design principles
- designing interactive AI applications using Streamlit

---

## ▶️ How to Run

```bash
streamlit run app.py

