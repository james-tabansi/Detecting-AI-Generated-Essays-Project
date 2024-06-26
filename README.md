# Detecting-AI-Generated-Essays-Project

## **Problem Statement:**

The proliferation of AI technologies has led to concerns regarding the authenticity of written content, particularly essays. This project addresses the need for robust classification models capable of distinguishing between essays generated by AI systems and those authored by humans. The objective is to develop and evaluate various machine learning and deep learning models for accurately classifying essays as either AI-generated or human-generated.

## **Objective:**

The primary objective of this project was to develop models that can effectively classify essays as either AI-generated or human-generated. To achieve this, we considered a range of machine learning and deep learning models, including decision trees, support vector machines (SVM), recurrent neural networks (RNNs), gated recurrent units (GRUs), long short-term memory (LSTM) networks, and BERT (Bidirectional Encoder Representations from Transformers). We evaluated the performance of these models based on key metrics such as Recall and AUC scores to assess their effectiveness in distinguishing between human and AI-generated essays.

## **Key Components:**

1. **Data Collection and Preprocessing:**
   We obtained a dataset of essays from Kaggle that included both human-authored and AI-generated samples. 

2. **Feature Extraction and Representation:**
   We extracted relevant features from the text data and representing them in a numerical formats suitable for model training. This may involve techniques such as Bag-of-Words (BoW), TF-IDF (Term Frequency-Inverse Document Frequency), word embeddings, or fine-tuning BERT embeddings.

3. **Model Training:**
   Experimenting with a variety of machine learning and deep learning models, including decision trees, SVM, RNNs, GRUs, LSTMs, and BERT-based models. Training these models on the labeled dataset to learn the patterns distinguishing human-authored essays from AI-generated ones.

4. **Evaluation Metrics:**
   We assessed the performance of the classification models using evaluation metrics specifically Recall and AUC scores. These metrics provide insights into the models' ability to correctly classify essays as human-generated or AI-generated, taking into account both true positive and false positive rates.

By systematically evaluating the performance of various classification models, this project aims to contribute to the development of reliable methods for detecting AI-generated essays. The insights gained from this research have implications for ensuring the integrity and authenticity of written content in various domains, including education, journalism, and content creation.
