# 📚 Book Recommender with LLMs

An AI-powered semantic book recommendation engine that uses large language models (LLMs), vector databases, and zero-shot classification to deliver personalized book suggestions based on user input.

This project explores modern NLP workflows including semantic search, emotion-based filtering, and dynamic classification, and presents the results in an interactive web interface using Gradio.

---

## 🔍 Core Features

- **Semantic Search:** Users can enter natural language queries (e.g., *"a book about revenge and justice"*) and receive high-quality recommendations based on vector similarity.
- **Zero-Shot Text Classification:** Books are automatically labeled as *fiction* or *non-fiction*, enabling flexible filtering.
- **Sentiment & Emotion Analysis:** Extracts tone (e.g., suspenseful, joyful, tragic) from book descriptions to allow emotion-based sorting.
- **Interactive Gradio App:** Clean user interface for querying and filtering books based on semantics, classification, and tone.
- **Cleaned & Structured Data:** Raw dataset was refined, filtered, and prepared to ensure meaningful and efficient vector search.

---

## 💡 What I Practiced

- Building and querying a **vector database** for semantic recommendation
- Implementing **zero-shot and sentiment classification** using LLMs
- Leveraging **LangChain** components for LLM pipeline orchestration
- Creating an **interactive user interface** with Gradio
- Using tools like **KaggleHub**, `transformers`, `chromadb`, and environment variables for secure deployment

---

## 🛠️ Tech Stack

- **Python 3.11**
- `transformers` / HuggingFace
- `langchain`
- `chromadb`
- `gradio`
- `kagglehub`
- `pandas`, `matplotlib`, `seaborn`

---

## 🚀 Getting Started

### 1. Install dependencies

```bash
pip install -r requirements.txt
````

### 2. Add your `.env` file

Create a `.env` file in the root directory with your OpenAI API key:

```
OPENAI_API_KEY=your-key-here
```

### 3. Run the app

```bash
python gradio-page.py
```

---

## 🖼️ Screenshots

> *(Add your screenshots in a `screenshots/` folder and reference them here)*

### 🔍 Search Interface

![Search Screenshot](./screenshots/search.png)

### 📖 Book Results

![Results Screenshot](./screenshots/results.png)

---

## 📊 Notebooks Included

* `data-setup.ipynb`: Data cleaning, structure analysis
* `vector-search-and-text-classification.ipynb`: Embedding generation + vector DB setup + Fiction / non-fiction zero-shot classification
* `sentiment-analysis.ipynb`: Emotion & tone tagging via LLMs

---

## Reason for doing this project

This project served as a deep dive into combining LLMs with structured recommendation logic, bridging the gap between raw text data and intelligent, user-aligned suggestions. It also sharpened my ability to integrate state-of-the-art NLP with interactive frontends.


