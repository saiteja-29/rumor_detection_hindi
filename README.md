# Hindi Fake News Detection in Social Media  

This project aims to address the spread of misinformation on social media by developing a robust machine learning-based system to detect fake news in Hindi text. With Hindi being spoken by over 600 million people, this project fills a crucial gap in linguistic research for fake news detection, primarily dominated by English-language studies.

## Authors  
- Siddhartha  
- Khushi Agarwal  
- Sai Teja  

## Supervisor  
- Prof. Abhishek Srivastava  

## Overview  

Fake news, or rumors, is unverified information that spreads quickly through social media, causing misinformation and confusion. The primary objective of this project is to identify and categorize fake news in Hindi social media posts using advanced natural language processing (NLP) and machine learning techniques.

## Features  
- **Data Preprocessing**:  
  Using NLP techniques such as text cleaning, stop-word removal, punctuation removal, and lemmatization.  
- **Contextual Embeddings**:  
  Generated using **IndicBERT** to understand the meaning of Hindi text.  
- **Feature Extraction**:  
  - **Sentiment Analysis**: Polarity extraction using **XLM-Roberta** multilingual model.  
  - **Latent Dirichlet Allocation (LDA)**: Topic modeling for document classification.  
  - **Named Entity Recognition (NER)**: Entity extraction using **Stanza**.  
- **Hierarchical Classification**:  
  - **Level-1 Classifier**: Combines features such as embeddings, sentiment, LDA scores, and NER counts.  
  - **Level-2 Classifier**: Uses **Support Vector Machines (SVM)**, **Random Forest**, and **BERT transformer** for final rumor classification.

## Methodology  
1. **Data Input**:  
   Hindi text data is loaded from a CSV file.  
2. **Preprocessing**:  
   Applied NLP techniques to clean and preprocess the data.  
3. **Feature Extraction**:  
   Generated embeddings, topic scores, sentiment labels, and NER counts.  
4. **Model Training**:  
   Trained classifiers (**SVM**, **Random Forest**, and **BERT transformer**) with comprehensive feature sets.  
5. **Evaluation**:  
   Measured model performance using evaluation metrics like accuracy.

## Results  
The model achieved promising results, with hyperparameter tuning improving accuracy and reliability. The final system classifies Hindi social media posts as either **rumor** or **non-rumor**.



### Tools and Frameworks  
- **IndicBERT**: Pretrained transformer model for contextual embeddings.  
- **XLM-Roberta**: Multilingual transformer for sentiment analysis.  
- **SVM and Random Forest**: Level-2 classifiers for final categorization.

## Conclusion  
This project provides an effective approach for detecting fake news in Hindi social media posts. By leveraging advanced NLP techniques and machine learning, it enhances the reliability of information shared online.

## Acknowledgments  
We thank **Prof. Abhishek Srivastava** for his guidance throughout this project.

