# ✈️ AI Travel Assistant

An intelligent AI-powered travel planner that generates personalized holiday itineraries using LLMs, vector search, and modern web technologies 🤖🌍

---

## 🌍 Overview

AI Travel Assistant is an intelligent travel planning application that helps users design personalized holiday itineraries effortlessly. Built using FastAPI, Streamlit, and LangChain, the system leverages vector search and Hugging Face language models to understand user preferences and generate context-aware travel plans.

The application processes travel-related data through embedding and vectorization techniques, enabling efficient semantic search and retrieval. By combining LLM-powered reasoning with structured data, it can recommend destinations, create day-wise schedules, and adapt plans based on user input.

Key features include:

* Personalized itinerary generation using LLMs
* Semantic search with vector embeddings
* Interactive UI powered by Streamlit
* FastAPI backend for scalable API integration
* Modular architecture using LangChain components

This project demonstrates the integration of modern AI tools to build a smart, end-to-end travel planning assistant.


---

## 🚀 Features

✨ Personalized travel itinerary generation  
🧠 LLM-powered intelligent responses  
🔍 Semantic search with vector embeddings  
📅 Smart day-wise planning  
⚡ FastAPI backend for scalable APIs  
🌐 Interactive UI with Streamlit  

---

## 🛠️ Tech Stack

- **Frontend:** Streamlit  
- **Backend:** FastAPI  
- **LLM:** Hugging Face Transformers  
- **Framework:** LangChain  
- **Embeddings:** Sentence Transformers (Hugging face LLm Model)
- **Vector Store:** Qdrant

---

## 📂 Project Structure

```

AITravelAssistant/
│── src/
│   ├── app.py            # Streamlit frontend
│   ├── main.py           # FastAPI entry point
│   ├── config.py         # Configuration settings
│   ├── embeddings.py     # Embedding model setup
│   ├── ingest.py         # Data ingestion & preprocessing
│   ├── retriever.py      # Semantic retrieval logic
│   ├── vectorstores.py   # Vector DB handling
│   ├── generator.py      # LLM response generation
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

### Start FastAPI backend

```bash
uvicorn src.main:app --reload
```

### Start Streamlit frontend

```bash
streamlit run src/app.py
```

---

## 🧠 How It Works

1. 📄 Data ingestion via `ingest.py`
2. ✂️ Text splitting & preprocessing
3. 🔢 Embeddings generated using transformer models
4. 📦 Stored in vector database
5. 🔍 Query processed via retriever
6. 🤖 LLM generates final travel plan

---

## 🔄 Workflow Architecture

```
User Input → Streamlit UI → FastAPI → Retriever → Vector DB
                                         ↓
                                      LLM (Generator)
                                         ↓
                                   Final Response
```

---

## 🔮 Future Improvements

* 🌐 Multi-language support
* 🗺️ Map & location integration
* ✈️ Real-time travel APIs (flights, hotels)
* 📱 Mobile-friendly UI
* 🧾 Export itinerary as PDF

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request.

---

## 📜 License

This project is licensed under the MIT License.

---

## 💡 Author

**Neel**
GitHub: [https://github.com/Neel-2002](https://github.com/Neel-2002)

---

⭐ If you found this project useful, please give it a star!

```
