# **📰Fake News Detection🔍**

A complete end-to-end pipeline to detect fake news using Python, advanced NLP techniques, and open-source transformer models.

---

## 🚀Project Overview

This repository provides all you need to build a fake-news detector:

1. **Exploratory Data Analysis** (`1_EDA.ipynb`)
2. **Text Preprocessing & Lemmatization** (`2_Preprocessing.ipynb`)
3. **Embedding Generation** (`3_Embeddings.ipynb`)
4. **Fine-tuning DistilBERT** (`4_Train_DistilBERT.ipynb`)
5. **Model Evaluation** (`5_Evaluation.ipynb`)

## Dataset
The model is fine-tuned on the [Fake and Real News Dataset (Kaggle)](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)

## **🛠️Installation**

1. **Clone the repo**:
   ```bash
   git clone https://github.com/yourusername/fake_news_detector.git
   cd fake_news_detector
   ```

2. **Creating Virtual Environment**:
   ```bash
   conda create -n fakeNews python==3.10 -y
   conda activate fakeNews
   ```

3. **Installing Dependencies**:
   ```bash
   pip install -r requirements.txt
   python -m spacy download en_core_web_sm
   ```

## **📓Notebook Overview**:
- **1_EDA.ipynb**: Data loading, label distribution, text-length analysis, word clouds.
- **2_Preprocessing.ipynb**: Clean text, remove noise, lemmatize via SpaCy.
- **3_Embeddings.ipynb**: Generate and save `all-MiniLM-L6-v2` embeddings.
- **4_Training.ipynb**: Tokenize, train DistilBERT with Hugging Face Trainer.
- **5_Evaluation.ipynb**: Inference on validation set, metrics, confusion matrix, ROC curve.
- **6_Example.ipynb**: Testing the model with real-life example
