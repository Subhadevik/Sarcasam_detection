# 🔍 Sarcasm Detection in Tamil — Multilingual NLP

Detecting sarcasm in **Tamil-language social media text** using state-of-the-art NLP models including DistilBERT, GRU, and LSTM.

> 📄 Related work published at **DravidianLangTech @ EACL 2025**

---

## 📌 About the Project

Sarcasm is one of the hardest challenges in sentiment analysis — especially in low-resource languages like Tamil. This project builds and compares multiple NLP models to detect sarcasm in Tamil text, with applications in:

- Customer feedback analysis
- Brand sentiment monitoring for Indian-market businesses
- Social media content moderation

---

## 🛠️ Tech Stack

| Component | Technology |
|---|---|
| Language | Python |
| Models | DistilBERT (fine-tuned), GRU, LSTM |
| NLP Library | HuggingFace Transformers |
| Data Processing | Pandas, NumPy |
| Notebook | Jupyter Notebook |

---

## 📊 Model Performance Comparison

| Model | F1 Score |
|---|---|
| **DistilBERT (fine-tuned)** | **0.74** ✅ Best |
| GRU | 0.63 |
| LSTM (baseline) | 0.56 |

> DistilBERT outperformed the LSTM baseline by **~18%**

---

## ⚙️ Pipeline Overview

```
Raw Tamil Text
     ↓
Preprocessing (tokenization, cleaning)
     ↓
Model Training (DistilBERT / GRU / LSTM)
     ↓
Evaluation (F1 Score, Accuracy)
     ↓
Sarcasm Detected ✅ / Not Detected ❌
```

---

## 🚀 Getting Started

### Prerequisites
```bash
Python 3.8+
Jupyter Notebook
```

### Installation
```bash
git clone https://github.com/Subhadevik/Sarcasam_detection.git
cd Sarcasam_detection
pip install transformers torch pandas numpy scikit-learn jupyter
```

### Run the Notebook
```bash
jupyter notebook
```
Open the `.ipynb` file and run all cells.

---

## 🌐 Why Tamil NLP?

Tamil is spoken by **80+ million people** globally but remains under-resourced in AI research. Models built for Tamil directly impact real-world applications for a massive user base that English-focused NLP tools ignore.

This pipeline is **language-agnostic** — with dataset changes, it can be adapted to any Dravidian language.

---

## 📄 Related Publication

**Tamil Political Multiclass Sentiment Analysis using Machine Learning**
*DravidianLangTech Workshop @ EACL 2025* — Co-author

---

## 👩‍💻 Author

**Subhadevi Krishnaraj**
- 🔗 [LinkedIn](https://www.linkedin.com/in/subhadevi-krishnaraj)
- 🐙 [GitHub](https://github.com/Subhadevik)
- 📧 subhadevi333@gmail.com
