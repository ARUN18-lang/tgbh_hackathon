# 🚀 TGBH Hackathon - Loan Eligibility & Financial Tips RAG Model

## 📌 Project Overview
This project is an AI-powered **Retrieval-Augmented Generation (RAG) system** designed to:
- **Check Loan Eligibility** using document-based retrieval.
- **Provide Financial Tips** using AI-driven insights.
- **Process Voice & Text Inputs** with Speech-to-Text (STT) and Text-to-Speech (TTS).
- **Support Multiple Languages** for translation & response generation.

The system integrates **LangChain, Groq AI, FAISS, PyAudio, Streamlit, and more** to deliver a seamless customer support experience.

---
## 🏗️ Project Structure
```
TGBH-HACKATHON/
│── app.py               # Streamlit Web Application
│── intent.py            # Intent classification & routing
│── rag.py               # RAG-based loan eligibility checking
│── serp.py              # Web search integration
│── stt.py               # Speech-to-Text processing
│── translate.py         # Language translation
│── translate2.py        # English translation processing
│── translate3.py        # Native language response handling
│── tts.py               # Text-to-Speech conversion
│── utils.py             # API key & utility functions
│── requirements.txt     # Python dependencies
│── README.md            # Project Documentation
└── 📂 data/              # PDF files & embeddings
```

---
## 🔧 Installation & Setup
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/ARUN18-lang/tgbh_hackathon.git
cd tgbh_hackathon
```
### **2️⃣ Create a Virtual Environment**
```bash
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate     # On Windows
```
### **3️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```
### **4️⃣ Set Up API Keys**
Create a `.env` file in the root directory and add your API keys:
```
GROQ_API_KEY=your_groq_api_key
SARVAM_API_KEY=your_sarvam_api_key
SERPER_API_KEY=your_serper_api_key
```

---
## 🚀 Running the Application
### **Start the Streamlit App**
```bash
streamlit run app.py
```
The app will launch in your browser at **`http://localhost:8501`**.

---
## 🛠️ Features & Functionality
### ✅ **1. Loan Eligibility Check (RAG Model)**
- Extracts details from **ICICI Bank loan documents**.
- Uses **FAISS** for vector search & LangChain’s QA pipeline.
- Provides **structured loan eligibility details**.

### ✅ **2. Financial Tips Generator**
- Uses **Groq AI** to generate financial advice.
- Retrieves web-based financial strategies.

### ✅ **3. Speech-to-Text (STT) & Multilingual Translation**
- Supports voice input **(Hindi, Tamil, Telugu, Kannada, English)**.
- Transcribes speech & translates into **English** for processing.

### ✅ **4. Text-to-Speech (TTS) for Responses**
- Converts AI-generated responses back into the **native language**.
- Supports multiple voices & accents.

---
## 🎯 Example Queries
| User Query | Functionality Triggered |
|------------|------------------------|
| "Am I eligible for a home loan?" | Loan Eligibility Check (RAG) |
| "Give me financial tips for saving money." | Financial Tips Agent |
| "Apply for a personal loan online?" | Loan Application Guidance |

---
## 🤖 Technologies Used
- **Python** (LangChain, OpenAI, FAISS, PyAudio, Streamlit)
- **Groq AI** (LLM-based query processing)
- **Sarvam AI** (Speech-to-Text, Text-to-Speech, Translation)
- **FAISS** (Vector search for document retrieval)
- **Streamlit** (Web UI for user interaction)

---
## 📬 Contact
For any issues or contributions, feel free to **create an issue** or **pull request** on GitHub!

🔗 **GitHub Repo:** [TGBH Hackathon](https://github.com/ARUN18-lang/tgbh_hackathon)

