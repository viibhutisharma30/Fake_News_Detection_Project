<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fake News Detection Project</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            line-height: 1.6;
        }
        h1, h2 {
            color: #333;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        li {
            margin: 10px 0;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: center;
        }
        th {
            background-color: #f4f4f4;
        }
    </style>
</head>
<body>
    <h1>Fake News Detection Project</h1>
    <h2>Enhancing Fake News Detection Using BERT and Machine Learning Models</h2>
    
    <h2>📌 Overview</h2>
    <p>Fake news spreads misinformation and impacts society negatively. This project enhances existing fake news detection models by integrating <strong>BERT (Bidirectional Encoder Representations from Transformers)</strong> alongside traditional <strong>Machine Learning (ML) models</strong> for improved accuracy and performance.</p>
    
    <h2>🚀 Key Features</h2>
    <ul>
        <li><strong>BERT-based classification:</strong> Uses pretrained BERT embeddings for better contextual understanding.</li>
        <li><strong>Optimized ML models:</strong> Hyperparameter tuning on XGBoost, Random Forest, and Naïve Bayes.</li>
        <li><strong>Hybrid Approach (BERT + XGBoost):</strong> Combining deep learning with ML for better generalization.</li>
        <li><strong>Improved accuracy:</strong> Achieves 87% accuracy compared to traditional models.</li>
    </ul>
    
    <h2>📊 Dataset Used</h2>
    <ul>
        <li><strong>LIAR Dataset</strong> – A benchmark dataset containing 12.8K labeled statements.</li>
        <li><strong>Preprocessing steps:</strong> Removing special characters, stopwords, and tokenization using BERT.</li>
    </ul>
    
    <h2>🔧 Implementation Details</h2>
    <h3>1. Traditional ML Model Optimization</h3>
    <ul>
        <li>Feature extraction using <strong>TF-IDF (bigrams & trigrams)</strong>.</li>
        <li>Hyperparameter tuning with <strong>GridSearchCV</strong>.</li>
    </ul>
    
    <h3>2. BERT-based Model Implementation</h3>
    <ul>
        <li>Fine-tuned <strong>BERT-base-uncased</strong> model.</li>
        <li>Optimized batch size, learning rate, and training epochs.</li>
    </ul>
    
    <h3>3. Hybrid Model (BERT + XGBoost)</h3>
    <ul>
        <li>Combines deep learning and ML for improved results.</li>
        <li>Uses a <strong>voting ensemble</strong> method.</li>
    </ul>
    
    <h2>📈 Results & Performance</h2>
    <table>
        <tr>
            <th>Model</th>
            <th>Previous Accuracy</th>
            <th>Improved Accuracy</th>
        </tr>
        <tr>
            <td>Naïve Bayes</td>
            <td>71%</td>
            <td>74%</td>
        </tr>
        <tr>
            <td>Random Forest</td>
            <td>73%</td>
            <td>77%</td>
        </tr>
        <tr>
            <td>XGBoost</td>
            <td>75%</td>
            <td>79%</td>
        </tr>
        <tr>
            <td><strong>BERT (New)</strong></td>
            <td>-</td>
            <td><strong>84%</strong></td>
        </tr>
        <tr>
            <td><strong>BERT + XGBoost (Hybrid)</strong></td>
            <td>-</td>
            <td><strong>87%</strong></td>
        </tr>
    </table>
    
    <h2>📌 Visualizations</h2>
    <ul>
        <li><strong>Confusion Matrix</strong> – To analyze misclassifications.</li>
        <li><strong>Accuracy Graphs</strong> – Showing performance improvements.</li>
        <li><strong>Feature Importance Analysis</strong> – Identifying key words influencing classification.</li>
    </ul>
    
    <h2>📚 References</h2>
    <ul>
        <li>Khanam, Z. et al. (2021). <em>Fake News Detection Using Machine Learning Approaches.</em></li>
        <li>Devlin, J. et al. (2019). <em>BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding.</em></li>
    </ul>
</body>
</html>
