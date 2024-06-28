# Paraphrase Identification Using Quora Question Pair

## Overview

This project addresses the problem of paraphrase identification to enhance data quality and reduce redundancy on platforms like Quora. By leveraging advanced machine learning techniques, specifically Siamese networks, the system identifies semantically similar questions, improving data storage and information quality.

## Project Description

### Objective

The main goal is to build a system that takes two texts as input and determines if they are semantically similar. This helps in reducing redundant data and improving user experience on digital platforms by presenting unique and relevant information.

### Approach

The project uses the Quora Question Pairs dataset, which consists of over 400,000 labeled samples. The dataset undergoes preprocessing, including resolving missing data fields, removing duplicates, and tokenization. Embeddings are generated using GloVe and FastText. A graph-based data augmentation strategy is employed to address class imbalance.

Several Siamese network models are designed using RNN, LSTM, GRU, and Transformer units. These models are evaluated based on accuracy, precision, recall, F1 score, and AUC.

## Key Features

- **Data Preprocessing**: Resolves data quality issues and generates embeddings.
- **Siamese Networks**: Utilizes advanced architectures for identifying semantic similarities.
- **Model Evaluation**: Comprehensive evaluation using multiple metrics.

## Impact

- **Accuracy Improvement**: Achieved an accuracy of 0.83 and an F1 score of 0.77.
- **Data Quality Enhancement**: Reduces redundant data on platforms like Quora.
- **Broader Applications**: Useful in plagiarism detection, content management, and improving user experience on digital platforms.

## Technology Stack

- **Data Sources**: Quora Question Pairs dataset.
- **Machine Learning Frameworks**: TensorFlow, GloVe, FastText.
- **Development Tools**: Jupyter Notebook, Google Cloud’s Vertex AI, Streamlit.

## Results

- **Model Performance**: The Transformer-based Siamese network model proved to be the most effective.
- **User Experience**: Improved the efficiency and relevance of information retrieval on Quora-like platforms.

## Conclusion

This project sets a new standard for digital content management, reducing redundancy, and improving data quality. The use of advanced machine learning techniques has proven effective in paraphrase identification, with significant implications for various applications in digital content management and plagiarism detection.
