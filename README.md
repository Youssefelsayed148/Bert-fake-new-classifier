# 🚀 Bert-Fake-News-Detector

A lightweight, encoder-only NLP project to **detect fake news headlines and articles**, trained using BERT on a balanced fake/real news dataset.  
This project demonstrates a typical workflow you’d use in real-world machine learning engineering, including:

- 🤗 Data loading and preprocessing with the Hugging Face Datasets library
- 🔥 Fine-tuning a pre-trained `bert-base-uncased` model for text classification
- 🏷 Mapping output labels to human-friendly `REAL` and `FAKE` tags
- 📈 Evaluating with metrics like accuracy and F1
- ☁️ Pushing the trained model to the Hugging Face Hub for easy sharing and reuse

---

## 🏗 Model details
| Component  | Value |
|------------|-------|
| Architecture | BERT (bert-base-uncased) |
| Task | Binary text classification |
| Labels | `REAL` and `FAKE` |
| Training Data | Balanced dataset of real vs fake news articles |
| Training Framework | 🤗 Transformers with PyTorch |
| Optimizations | fp16 training, early stopping, dynamic padding |

---

## 🚀 Usage
You can load and run inference directly with 🤗 Transformers pipelines:
Read summary.py for an example

