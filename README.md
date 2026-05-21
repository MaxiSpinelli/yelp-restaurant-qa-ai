
# Yelp Restaurant Q&A and Recommender System

An AI-powered question-answering and recommendation system built in Python, leveraging large-scale Yelp datasets from the US and Canada to deliver tailored restaurant suggestions based on natural language user queries.

## 🚀 Project Overview
This project processes restaurant data and user reviews from Yelp to build an intelligent assistant. Users can ask questions in plain English (e.g., *"Where can I find the best crispy tacos in Toronto with outdoor seating?"*) and receive precise, data-driven recommendations.

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Environment:** Jupyter Notebook
* **LLM Engine:** `Ollama` (Local LLM execution)
* **Vector Database:** `ChromaDB` (For semantic search and document embeddings)
* **Data Manipulation:** `pandas`, `numpy`

## 📊 Dataset
The system uses the official **Yelp Dataset**, focusing specifically on businesses, reviews, and user data within North America (US & Canada). Key preprocessing steps included:
* Filtering and cleaning text reviews.
* Geographic segmentation (focusing on specific culinary hubs).
* Structure optimization for efficient query matching.

## 💡 Key Features
* **Natural Language Understanding:** Interprets subjective user preferences beyond simple category tags.
* **Contextual Matching:** Ranks restaurants based on review sentiment, specific keywords, and metadata (location, stars).
* **Interactive QA:** Provides structured answers explaining *why* a restaurant was recommended.

## 🏁 How to Run
1. Clone this repository:
   ```bash
   git clone [https://github.com/MaxiSpinelli/yelp-restaurant-qa-ai.git](https://github.com/MaxiSpinelli/yelp-restaurant-qa-ai.git)
