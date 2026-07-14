TASK 1 Readme.txt
# News Topic Classifier Using BERT

## Objective

The objective of this project is to build a News Topic Classification model using the BERT (Bidirectional Encoder Representations from Transformers) model. The model classifies news headlines into one of four categories: World, Sports, Business, and Science/Technology.

This project demonstrates the use of transfer learning with transformer models for Natural Language Processing (NLP).

---

##  Dataset

**AG News Dataset**

Source:
https://huggingface.co/datasets/ag_news

The dataset contains over 120,000 news articles categorized into four classes:

- World
- Sports
- Business
- Science/Technology

---

## Technologies Used

- Python
- Google Colab
- Hugging Face Transformers
- Hugging Face Datasets
- PyTorch
- Scikit-learn
- Gradio

---

## Methodology

1. Loaded the AG News dataset using Hugging Face Datasets.
2. Preprocessed and tokenized text using the BERT tokenizer.
3. Fine-tuned the pre-trained `bert-base-uncased` model.
4. Evaluated the model using Accuracy and Weighted F1-score.
5. Saved the trained model.
6. Developed a Gradio interface for real-time news classification.

---

## Evaluation Metrics

- Accuracy
- Weighted F1 Score
- Classification Report
- Confusion Matrix

---

## Project Structure
```
Task_1_BERT_News_Classifier/
│
├── Task_1_BERT_News_Classifier.ipynb
├── bert_news_model/
├── README.md
└── requirements.txt
```

---

##  Key Results

- Successfully fine-tuned a BERT model for text classification.
- Achieved strong classification performance on the AG News dataset.
- Built an interactive interface using Gradio.

---

## Skills Gained

- Natural Language Processing
- Transformer Models
- BERT Fine-tuning
- Text Classification
- Model Evaluation
- Gradio Deployment

---

## 👨‍💻 Author

Developed as part of the AI/ML Engineering Internship at DevelopersHub Corporation.
