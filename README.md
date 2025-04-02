Enhancing Fake News Detection Using BERT and Machine Learning Models <br>
📌 Overview 
Fake news spreads misinformation and impacts society negatively. This project enhances existing fake news detection models by integrating BERT (Bidirectional Encoder Representations from Transformers) alongside traditional Machine Learning (ML) models for improved accuracy and performance.<br>

🚀 Key Features <br>
1.BERT-based classification: Uses pretrained BERT embeddings for better contextual understanding.<br>
2.Optimized ML models: Hyperparameter tuning on XGBoost, Random Forest, and Naïve Bayes. <br>
3.Hybrid Approach (BERT + XGBoost): Combining deep learning with ML for better generalization.<br> 
4.Improved accuracy: Achieves 87% accuracy compared to traditional models.<br>

📊 Dataset Used <br>
1.LIAR Dataset – A benchmark dataset containing 12.8K labeled statements.<br>
2.Preprocessing steps: Removing special characters, stopwords, and tokenization using BERT.<br><br>

🔧 Implementation Details <br>
1.Traditional ML Model Optimization a)Feature extraction using TF-IDF (bigrams & trigrams). b)Hyperparameter tuning with GridSearchCV.<br>
2.BERT-based Model Implementation a)Fine-tuned BERT-base-uncased model. b)Optimized batch size, learning rate, and training epochs.<br>
3.Hybrid Model (BERT + XGBoost) a)Combines deep learning and ML for improved results. b)Uses a voting ensemble method.<br><br>

📈 Results & Performance Model<br>
Previous Accuracy Improved Accuracy<br>
Naïve Bayes 71% 74% <br>
Random Forest 73% 77% <br>
XGBoost 75% 79% <br>
BERT (New) - 84% <br>
BERT + XGBoost (Hybrid) - 87%<br><br>

📌 Visualizations<br>
Confusion Matrix – To analyze misclassifications.<br>
Accuracy Graphs – Showing performance improvements. <br>
Feature Importance Analysis – Identifying key words influencing classification.<br><br>

📚 References<br> 
1.Khanam, Z. et al. (2021). Fake News Detection Using Machine Learning Approaches.<br>
2.Devlin, J. et al. (2019). BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding.<br>
