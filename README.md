# 🎯 Feedback Sentiment Analysis

> An NLP-based Sentiment Analysis system powered by **DistilBERT** (Hugging Face Transformers) that classifies text feedback as **POSITIVE** or **NEGATIVE** with a confidence score — supporting both single-sentence and long-text analysis.

---

## 🚀 Overview

This project leverages a **pre-trained Transformer model** (`distilbert-base-uncased-finetuned-sst-2-english`) from Hugging Face to perform real-time sentiment classification on user feedback, product reviews, and custom text inputs.

Unlike traditional ML approaches (TF-IDF + Logistic Regression), this project uses **state-of-the-art Deep Learning** — making it production-grade and highly accurate.

---

## ✨ Features

- 🤖 **Transformer-based NLP** — Uses DistilBERT, a lightweight BERT variant fine-tuned on SST-2
- 📊 **Confidence Scoring** — Returns sentiment label + confidence score for every prediction
- 💬 **Custom Text Input** — Accepts real-time user input for sentiment prediction
- 📝 **Long Text Support** — Handles multi-sentence paragraph analysis
- ⚡ **Fast Inference** — DistilBERT is 40% smaller and 60% faster than BERT

---

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| **Language** | Python 3.x |
| **NLP / AI** | Hugging Face Transformers, DistilBERT |
| **Deep Learning** | PyTorch (via Transformers pipeline) |
| **Environment** | Google Colab, Jupyter Notebook |

---

## 📁 Project Structure

```
feedback-sentiment-analysis/
│
├── Sentiment_Analysis.ipynb     # Main notebook with full implementation
├── sentiment-analysis1.png      # Output screenshot 1
├── sentiment-analysis2.png      # Output screenshot 2
├── sentiment-analysis3.png      # Output screenshot 3
└── README.md
```

---

## 🤖 Model Details

| Property | Detail |
|---|---|
| **Model** | `distilbert-base-uncased-finetuned-sst-2-english` |
| **Source** | Hugging Face Model Hub |
| **Type** | Transformer (DistilBERT) |
| **Task** | Sentiment Classification |
| **Output** | POSITIVE / NEGATIVE + Confidence Score |

---

## 📊 Example Output

```python
Text: "I love this product! It's amazing."
Sentiment: POSITIVE
Confidence: 0.9998

Text: "The service was terrible and I'm very disappointed."
Sentiment: NEGATIVE
Confidence: 0.9997

Text: "It's okay, not great but not bad either."
Sentiment: NEGATIVE
Confidence: 0.6923
```

---

## ▶️ How to Run

### Option 1: Google Colab (Recommended)
1. Open `Sentiment_Analysis.ipynb` in Google Colab
2. Run all cells (`Runtime → Run all`)
3. Enter custom text when prompted

### Option 2: Local Setup
```bash
# Install dependencies
pip install transformers torch

# Run the script
python sentiment_analysis.py
```

---

## 💡 Key Learnings

- Implemented **Transformer-based NLP** using Hugging Face pipelines
- Applied **pre-trained DistilBERT** model for sentiment classification — understanding transfer learning in NLP
- Built **real-time custom text inference** with confidence scoring
- Explored **long-text sentiment analysis** for multi-sentence inputs
- Understood the advantage of **Transformer models over traditional ML** (TF-IDF + classical classifiers)

---

## 👩‍💻 Author

**Jassica Thakur**
- 📧 thakurjassica11@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/jassica-thakur)
- 🐙 [GitHub](https://github.com/jassica7)

---

## ⭐ If you found this project useful, please give it a star!
