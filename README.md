# Fake_News_Detection_Project
Enhancing Fake News Detection Using BERT and Machine Learning Models
📌 Overview
Fake news spreads misinformation and impacts society negatively. This project enhances existing fake news detection models by integrating BERT (Bidirectional Encoder Representations from Transformers) alongside traditional Machine Learning (ML) models for improved accuracy and performance.

🚀 Key Features
1.BERT-based classification: Uses pretrained BERT embeddings for better contextual understanding.
2.Optimized ML models: Hyperparameter tuning on XGBoost, Random Forest, and Naïve Bayes.
3.Hybrid Approach (BERT + XGBoost): Combining deep learning with ML for better generalization.
4.Improved accuracy: Achieves 87% accuracy compared to traditional models.

📊 Dataset Used
1.LIAR Dataset – A benchmark dataset containing 12.8K labeled statements.
2.Preprocessing steps: Removing special characters, stopwords, and tokenization using BERT.

🔧 Implementation Details
1.Traditional ML Model Optimization
a)Feature extraction using TF-IDF (bigrams & trigrams).
b)Hyperparameter tuning with GridSearchCV.

2.BERT-based Model Implementation
a)Fine-tuned BERT-base-uncased model.
b)Optimized batch size, learning rate, and training epochs.

3.Hybrid Model (BERT + XGBoost)
a)Combines deep learning and ML for improved results.
b)Uses a voting ensemble method.

📈 Results & Performance
Model	Previous Accuracy	Improved Accuracy
Naïve Bayes	71%	74%
Random Forest	73%	77%
XGBoost	75%	79%
BERT (New)	-	84%
BERT + XGBoost (Hybrid)	-	87%

📌 Visualizations
Confusion Matrix – To analyze misclassifications.
Accuracy Graphs – Showing performance improvements.
Feature Importance Analysis – Identifying key words influencing classification.

📚 References
Khanam, Z. et al. (2021). Fake News Detection Using Machine Learning Approaches.

Devlin, J. et al. (2019). BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding.


