
# ✈️ AI Travel Assistant

An intelligent travel planning app that creates personalized holiday itineraries using AI 🤖

---

## 🌍 Overview

AI Travel Assistant helps users plan trips effortlessly by generating customized travel itineraries based on preferences. It combines LLMs, vector search, and modern web frameworks to deliver smart, context-aware recommendations.

---

## 🚀 Features

✨ Personalized itinerary generation  
🧠 LLM-powered travel recommendations  
🔍 Semantic search using vector embeddings  
📅 Day-wise trip planning  
🌐 Interactive UI with Streamlit  
⚡ FastAPI backend for scalability  

---

## 🛠️ Tech Stack

- **Frontend:** Streamlit  
- **Backend:** FastAPI  
- **LLM:** Hugging Face Transformers  
- **Framework:** LangChain  
- **Vector DB:** (FAISS / Chroma / your choice)  
- **Embeddings:** Sentence Transformers  

---

## 📂 Project Structure

```

AiTravelAssistant/
│── src/
│   ├── main.py          # FastAPI entry point
│   ├── ingest.py        # Data ingestion & vectorization
│   ├── generator.py     # LLM response generation
│── app.py               # Streamlit UI
│── requirements.txt
│── README.md

````

---

## ⚙️ Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Neel-2002/AITravelAssistant.git
cd AITravelAssistant
````

### 2️⃣ Create virtual environment

```bash
python -m venv venv
venv\Scripts\activate
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Application

### Start FastAPI server

```bash
uvicorn src.main:app --reload
```

### Start Streamlit app

```bash
streamlit run app.py
```

---

## 🧠 How It Works

1. 📄 Travel data is ingested and split into chunks
2. 🔢 Text is converted into embeddings
3. 📦 Stored in a vector database
4. 🔍 User query is matched using semantic search
5. 🤖 LLM generates a personalized response

---

## 📸 Demo (Optional)

*Add screenshots or GIFs here*

---

## 🔮 Future Improvements

* 🌐 Multi-language support
* 🗺️ Map integration
* 📱 Mobile-friendly UI
* ✈️ Real-time flight & hotel APIs

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a PR.

---

## 📜 License

This project is licensed under the MIT License.

---

## 💡 Author

**Neel**
GitHub: [https://github.com/Neel-2002](https://github.com/Neel-2002)

---

⭐ If you like this project, don’t forget to star the repo!

```

Just tell me 👍
```
