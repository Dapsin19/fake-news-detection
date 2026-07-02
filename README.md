# 📰 Fake News Detection AI

An AI-powered fake news detection system that uses Transformer-based Natural Language Processing (NLP) models to classify news articles and provide confidence scores through a FastAPI REST API.

---

## 📌 Overview

This project demonstrates an end-to-end NLP application for detecting potentially misleading news articles using pretrained Transformer models from Hugging Face.

The system accepts news text as input, performs inference using a Transformer model, and returns:

* News classification
* Prediction confidence score
* Human-readable explanation

This project showcases practical Machine Learning engineering skills including API development, NLP inference, and model deployment.

---

## 🚀 Features

* ✅ Fake news classification
* ✅ Transformer-based NLP model
* ✅ Confidence score for every prediction
* ✅ Explainable prediction output
* ✅ REST API built with FastAPI
* ✅ Ready for deployment

---

## 🧠 Tech Stack

* Python
* FastAPI
* Hugging Face Transformers
* PyTorch
* NumPy

---

## 📂 Project Structure

```text
fake-news-detection-ai/
│
├── app.py
├── model.py
├── requirements.txt
├── README.md
├── LICENSE
├── .gitignore
│
├── sample_data/
│   └── example_news.txt
│
└── tests/
    └── test_api.py
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/Dapsin19/fake-news-detection-ai.git
cd fake-news-detection-ai
```

Install the required packages:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the API

Start the FastAPI server:

```bash
uvicorn app:app --reload
```

Open the interactive API documentation:

```text
http://127.0.0.1:8000/docs
```

---

## 📥 Example Request

```json
{
  "text": "The European Commission announced a €2 billion investment in artificial intelligence research."
}
```

---

## 📤 Example Response

```json
{
  "prediction": "REAL",
  "confidence_score": 0.94,
  "explanation": "The model identified linguistic patterns consistent with credible news reporting."
}
```

---

## 🧪 Running Tests

Execute the test suite with:

```bash
pytest
```

---

## 📊 Example Use Cases

* Social media content moderation
* Fake news detection
* Trust and safety systems
* News verification pipelines
* Content filtering
* NLP research and experimentation

---

## 🔮 Future Improvements

* Fine-tune BERT, RoBERTa, or DistilBERT on the FakeNewsNet dataset.
* Add support for batch predictions.
* Deploy the API using Docker and cloud platforms.
* Store prediction history in a database.
* Add explainability techniques such as SHAP or LIME.
* Build a web interface for interactive testing.

---

## 👨‍💻 Author

**Adedapo Balogun**

Machine Learning Engineer | Data Scientist | MLOps Enthusiast

* GitHub: https://github.com/Dapsin19
* LinkedIn: https://www.linkedin.com/in/adedapo-adedire-071707188/

---

## 📄 License

This project is licensed under the MIT License.
