# 🤖 Personal Finance Assistant

**Personal Finance Assistant** is a multi-model AI chatbot designed to provide intelligent, context-aware financial insights. It combines a large language model with specialized NLP models to understand financial questions, analyze sentiment, and identify important financial entities.

## ✨ Features

* 💬 **Financial Q&A** – Uses LLaMA to answer finance-related questions.
* 🧠 **Sentiment Analysis** – Uses BERT to analyze sentiment in financial text.
* 🏷️ **Financial Entity Recognition** – Uses BERT NER to identify financial entities such as companies, organizations, stocks, and monetary values.
* 🔄 **Multi-Model AI** – Combines multiple NLP models for improved financial text understanding.
* 💡 **Financial Insights** – Generates context-aware responses to user queries.
* 🖥️ **Interactive Interface** – Streamlit-based interface for interacting with the chatbot.

## 🛠️ Technologies Used

* Python
* PyTorch
* HuggingFace Transformers
* LLaMA
* BERT
* BERT NER
* Streamlit

## 📊 Datasets

* **FiQA-2018** – Financial question answering and sentiment analysis
* **Financial PhraseBank** – Financial sentiment classification
* **FinNER** – Financial named entity recognition

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/heshmasree2809/Personal-Finance-Assistant.git
cd Personal-Finance-Assistant
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

## ▶️ Run the Application

```bash
streamlit run app.py
```

## 🔄 How It Works

```text
User Financial Query
        ↓
   Text Processing
        ↓
 ┌──────┴─────────┐
 ↓                ↓
BERT           BERT NER
Sentiment      Entity Extraction
 ↓                ↓
 └──────┬─────────┘
        ↓
     Context
        ↓
      LLaMA
        ↓
Financial Response
        ↓
      User
```

## 🎯 Objective

The goal of this project is to demonstrate how **LLMs and specialized NLP models can work together** to build an intelligent financial assistant capable of understanding financial queries, sentiment, and domain-specific entities.

## ⚠️ Disclaimer

This project is developed for **educational and research purposes**. The generated information should not be considered professional financial, investment, or legal advice.

---

## ⭐ Support

If you find this project useful or interesting, please consider giving it a **⭐ Star** on GitHub!

Your support is greatly appreciated and motivates me to build and improve more AI projects. 🚀

**Made with ❤️ using Python, NLP & Generative AI**
