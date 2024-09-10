---
layout: page
title: Movie recommendation system
description: Using deep reinforcement learning to understand animal behaviors
img: assets/img/movie.jpg
importance: 1
category: academic
---

## Overview
This project focused on developing an advanced machine learning model for sentiment analysis and movie recommendations by processing a dataset of over 10,000 IMDB movie reviews. The primary goal was to enhance the accuracy and relevance of the system's recommendations while improving the precision of sentiment classification.

## Problem Statement
Sentiment analysis is crucial for understanding user feedback and improving recommendation systems. Traditional models often struggle with processing large-scale textual data efficiently, leading to slow and sometimes inaccurate recommendations. This project aimed to develop a more precise, efficient model to process and categorize IMDB reviews, ensuring quicker and more relevant movie recommendations.

## Approach & Methodology
1. **Text Processing with TF-IDF Vectorization**: The reviews were processed using Term Frequency-Inverse Document Frequency (TF-IDF) vectorization to transform the textual data into numerical features, highlighting the importance of words relative to their frequency in the dataset.
2. **Clustering with K-Means**: The processed data was then categorized using K-Means clustering, which grouped similar reviews together. This categorization helped in identifying underlying patterns and trends in movie preferences, contributing to more relevant recommendations.
3. **Dimensionality Reduction with PCA**: To optimize performance and efficiency, Principal Component Analysis (PCA) was applied for dimensionality reduction. This process preserved over 90% of the data’s variance while reducing the number of features, significantly speeding up the analysis.
4. **Model Optimization**: Rigorous accuracy testing was performed to fine-tune the model. Hyperparameter tuning was applied to ensure the highest precision in both sentiment classification and recommendation quality. The final model achieved a balance between speed and accuracy, cutting manual analysis time by 50%.

## Tools & Technologies Used
- **Programming Language**: Python
- **Machine Learning Libraries**: Scikit-learn, Pandas, Numpy
- **Natural Language Processing**: TF-IDF Vectorization
- **Clustering Algorithm**: K-Means
- **Dimensionality Reduction**: Principal Component Analysis (PCA)
- **Evaluation Metrics**: Precision, Recall, F1-score

## Results & Impact
- **Accuracy Improvement**: The TF-IDF and K-Means-based model significantly improved the precision of sentiment analysis.
- **Efficiency**: The use of PCA for dimensionality reduction halved the time required for manual analysis while retaining over 90% of data variance.
- **Enhanced Recommendations**: The clustering-based categorization resulted in more relevant movie recommendations for users, aligning better with their preferences.

## Key Takeaways
This project demonstrated the power of combining machine learning techniques like TF-IDF vectorization, clustering, and dimensionality reduction to improve both the accuracy and efficiency of sentiment analysis and recommendation systems. It highlighted the importance of data preprocessing and model fine-tuning to deliver precise, impactful results.

## Skills Demonstrated
+ Natural Language Processing (NLP)
+ Machine Learning (Clustering, Dimensionality Reduction)
+ Data Preprocessing and Feature Engineering
+ Model Optimization and Accuracy Testing
