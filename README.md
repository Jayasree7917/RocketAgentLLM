# 🚀 Intelligent Rocket Launch Advisor

### AI-Powered Weather Analysis & Launch Decision Support

## Overview
Developed an AI-powered agent that combines historical weather analysis, real-time weather APIs, LSTM-based temperature forecasting, and Retrieval-Augmented Generation (RAG) to assess weather conditions and generate explainable rocket launch recommendations.

## Key Features
- **LSTM Forecasting:** Predicts future temperatures using historical weather time-series data.
- **RAG Pipeline:** Uses SentenceTransformers embeddings and FAISS for semantic retrieval of similar historical weather patterns.
- **Hybrid Decision Engine:** Combines rule-based weather thresholds with an LLM to generate context-aware recommendations.
- **Real-Time Integration:** Retrieves weather data for specified geographical coordinates through weather APIs.
- **Natural Language Explanations:** Uses FLAN-T5 to translate weather data and retrieved context into concise, human-readable assessments.

## Tech Stack
**Python, TensorFlow/Keras, LSTM, Hugging Face Transformers, SentenceTransformers, FAISS, Pandas, NumPy, OpenWeatherMap API, Open-Meteo API**

## Workflow
Historical Weather Data → LSTM Forecasting → Live Weather Retrieval → FAISS-Based Similarity Search → Rule-Based Evaluation → LLM-Generated Recommendation

**Note:** This project is an experimental decision-support prototype, not a certified rocket launch safety system.

## Author
**Maddu Jayasree** | [GitHub](https://github.com/Jayasree7917)
