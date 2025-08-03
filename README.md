# 🦾 Digital Financial Literacy AI Agent


An AI-powered assistant built using **IBM Watsonx.ai** and **Retrieval-Augmented Generation (RAG)** to help users understand and navigate digital finance **safely and confidently**. This multilingual agent offers grounded responses from trusted documents (like RBI and NPCI guidelines) to promote financial literacy and prevent digital fraud.
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

> <img width="970" height="502" alt="image" src="https://github.com/user-attachments/assets/c3396496-7743-4f6a-9587-3b5a7b1f8b0c" />
> <img width="1184" height="477" alt="image" src="https://github.com/user-attachments/assets/c6f11b22-8262-42a9-b26c-fc7111c9c9a8" />
> <img width="1359" height="611" alt="image" src="https://github.com/user-attachments/assets/e57a9e61-b321-483c-a24a-06ca9dea948e" />
> <img width="1345" height="140" alt="image" src="https://github.com/user-attachments/assets/7298d20c-42ef-4b82-90e7-8f4a705c3ea2" />





---

## 🛠️ Setup Instructions

> _**Note:** This project is built and deployed using IBM Watsonx and IBM Cloud._  
> _Make sure you have access to an [IBM Cloud Lite Account](https://cloud.ibm.com/registration)._  

### 1. Clone the Repo

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

## 2. Upload Financial Documents

Upload **RBI**, **NPCI**, or any other trusted financial guideline PDFs to **IBM Cloud Object Storage**.  
These documents form the core knowledge base for the Retrieval-Augmented Generation (RAG) system.

## 3. Create Watsonx Project

1. Log in to [IBM Cloud](https://cloud.ibm.com/) and navigate to **Watsonx.ai Studio**  
2. Create a new **Watsonx Project**
3. Add the **Granite LLM model** to your project
4. Use the **Watsonx Vector Index** service to upload your documents  
5. Index your documents to enable semantic search through RAG

## 4. Connect LLM with Vector Index (RAG Setup)

- Link your **Granite LLM** with the **Watsonx Vector Index**
- Configure the **RAG pipeline** to ensure that user queries fetch the most relevant document chunks
- Test with queries like `"What is UPI fraud?"` to verify grounded answers

## 5. Deploy the Agent

Choose your preferred deployment method:

- 💬 **Chatbot Interface** – Build using React, Node.js, or Python (Flask/FastAPI)
- 📱 **WhatsApp/Telegram Bot** – Integrate using Twilio, Botpress, or other frameworks
- 🔗 **REST API** – Expose an API endpoint to serve third-party web/mobile apps

---

## 📈 Future Improvements

- 🌍 Add support for **regional languages** (Hindi, Tamil, Bengali, Marathi, etc.)
- 📲 Develop a **mobile-friendly chatbot UI**
- 📊 Create an **admin dashboard** to analyze user queries and feedback
- 🧾 Build **interactive financial guides** for budgeting, saving, UPI, and EMI calculators
- 🔐 Implement **enhanced privacy features** and secure query logging

