# 🦾 Digital Financial Literacy AI Agent
---
An AI-powered assistant built using **IBM Watsonx.ai** and **Retrieval-Augmented Generation (RAG)** to help users understand and navigate digital finance **safely and confidently**. This multilingual agent offers grounded responses from trusted documents (like RBI and NPCI guidelines) to promote financial literacy and prevent digital fraud.
---

---

## 🧩 Problem Statement

Millions in rural and underserved areas face challenges in understanding digital finance tools such as:

- UPI transactions
- Online frauds & scams
- Loan safety and interest rates
- Personal budgeting & investments

Lack of accessible, trustworthy financial knowledge leads to poor decisions, scams, and digital exclusion.

---

## 💡 Solution

This AI Agent leverages **IBM Watsonx.ai**, **Granite LLM**, and **document retrieval (RAG)** to deliver clear, document-backed financial guidance. It provides safe and grounded answers in a conversational format, tailored to users’ queries—even in multiple languages.

---

## 🧠 Tech Stack

- 💬 **IBM Watsonx.ai Studio** – Model deployment & management  
- 🧠 **Granite Foundation Model (LLM)** – Language understanding  
- 📚 **Watsonx Vector Index (RAG)** – Document-based Q&A  
- ☁️ **IBM Cloud Object Storage** – Secure PDF/document storage  
- 🔤 **Natural Language Processing (NLP)** – Intent recognition, multi-language support  
- 📄 **PDFs from RBI/NPCI/SEBI** – Trusted data sources

---

## ☁️ IBM Cloud Services Used

- Watsonx.ai Studio  
- Watsonx Granite LLM  
- Watsonx Vector Database  
- IBM Cloud IAM  
- IBM Cloud Object Storage  
- IBM Cloud Lite (Free Tier)

---

## 👥 Target Users

- 🧑‍🌾 Rural & semi-urban citizens  
- 🎓 Students & first-time earners  
- 👨‍👩‍👧‍👦 Self-help groups & women collectives  
- 🏫 Educational institutions & NGOs  
- 📱 General public using UPI/digital finance tools  
- 🏢 Customer service centers looking to automate financial Q&A

---

## 🔑 Features

- ✅ **Document-grounded Q&A** using vector similarity  
- ✅ **Polite handling of off-topic queries**  
- ✅ **Multilingual support** (coming soon)  
- ✅ **Answers based on trusted RBI/NPCI documents**  
- ✅ Covers **UPI safety**, **loans**, **scams**, **budgeting**, **interest rates**, and more  
- ✅ Built fully using **IBM Cloud stack**

---

## 🚀 How It Works

1. User types a query (e.g., "How to avoid UPI fraud?")
2. Granite LLM processes the input using NLP
3. Vector Index retrieves the most relevant chunk from uploaded financial PDFs
4. Agent replies with an easy-to-understand, grounded explanation
5. Handles irrelevant queries by politely redirecting the user

---

## 📸 Screenshots

> (Add screenshots of your UI/Chatbot interface here)

---

## 🛠️ Setup Instructions

> _**Note:** This project is built and deployed using IBM Watsonx and IBM Cloud._  
> _Make sure you have access to an [IBM Cloud Lite Account](https://cloud.ibm.com/registration)._  

### 1. Clone the Repo

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
