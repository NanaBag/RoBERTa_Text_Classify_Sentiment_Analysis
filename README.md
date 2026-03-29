# RoBERTa Text Classification for Intelligent Document Processing (UiPath Integration)

## Overview
This project implements a **RoBERTa-based NLP model** for text classification and sentiment analysis, integrated with **UiPath automation workflows** to enable intelligent document processing.

The solution combines **Machine Learning (RoBERTa)** with **Robotic Process Automation (UiPath)** to classify, route, and process unstructured text data efficiently.

---

## Problem Statement
Traditional RPA systems struggle with unstructured text (emails, invoices, customer feedback).  
This project solves that by introducing **context-aware NLP classification** using transformer models.

---

## Solution Architecture
- **RoBERTa Model** → Performs text classification / sentiment analysis
- **Python Backend** → Handles preprocessing, inference, and API exposure
- **UiPath Workflow** → Consumes model output and automates decision-making

### Workflow:
1. Input text (email / document / feedback)
2. Preprocessing (tokenization, cleaning)
3. RoBERTa inference
4. Classification output (e.g., Positive / Negative / Category)
5. UiPath triggers automation based on prediction

---

## Technologies Used
- Python
- Hugging Face Transformers
- RoBERTa
- PyTorch
- UiPath (RPA)
- REST API (Flask / FastAPI)
- Pandas, NumPy

---

## Key Features
- Context-aware text classification using RoBERTa
- High accuracy compared to traditional ML models
- Seamless integration with UiPath workflows
- Scalable API-based architecture
- Real-time inference capability

---

## Model Details
- Pretrained Model: `roberta-base`
- Fine-tuned on custom dataset for classification
- Task: Sentiment Analysis / Multi-class Classification

---

## Installation

```bash
git clone https://github.com/NanaBag/RoBERTa_Text_Classify_Sentiment_Analysis.git
cd RoBERTa_Text_Classify_Sentiment_Analysis
pip install -r requirements.txt
