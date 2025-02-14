# Sentiment Analysis with ParsBERT

![Project Status](https://img.shields.io/badge/Status-Completed-green) ![Contributions](https://img.shields.io/badge/Contributions-Welcome-brightgreen)

## 📌 Project Overview
This repository contains an advanced sentiment analysis project focusing on Persian text, specifically user reviews from SnappFood, an online food delivery platform in Iran. The project utilizes **ParsBERT**, a transformer-based model fine-tuned for Persian sentiment classification. By implementing optimization techniques, it significantly improves classification accuracy and robustness.

## 🚀 Features
- **Advanced preprocessing techniques** for handling informal language
- **Optimized hyperparameters** for improved accuracy
- **Performance evaluation using Precision, Recall, F1-score, and Accuracy**
- **92.5% accuracy** achieved on SnappFood dataset

## 🛠️ Technologies Used
- Python 🐍
- TensorFlow & PyTorch 🔥
- ParsBERT (Transformer-based NLP model for Persian) 🤖
- Pandas & NumPy for data preprocessing 📊
- Matplotlib & Seaborn for visualization 📈

## 🏗️ Installation & Setup
To get started with this project, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/sentiment-analysis-parsbert.git
   cd sentiment-analysis-parsbert
   ```
2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # For macOS/Linux
   venv\Scripts\activate     # For Windows
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run Jupyter Notebook to explore the analysis:
   ```bash
   jupyter notebook
   ```

## 📊 Results
The optimized ParsBERT model achieved **92.5% accuracy** on the SnappFood dataset, improving upon previous benchmarks. The performance metrics are as follows:

| Metric      | Score  |
|------------|--------|
| Accuracy   | 92.48% |
| Precision  | 92.52% |
| Recall     | 92.48% |
| F1-Score   | 92.48% |

## 🔬 Methodology
1. **Preprocessing:**
   - Text normalization for handling informal Persian language
   - Stopword removal and punctuation cleaning
   - Handling spelling variations & mixed sentiments
2. **Model Training:**
   - Hyperparameter tuning
   - Regularization techniques (dropout, L2 weight decay)
3. **Evaluation:**
   - Performance measured using classification metrics (Precision, Recall, F1-score)
   - ROC-AUC curve analysis

## 📜 References
- [ParsBERT Paper](https://arxiv.org/abs/2005.12515)
- [SnappFood Sentiment Analysis Dataset](https://www.kaggle.com/datasets/soheiltehranipour/snappfood-persian-sentiment-analysis)
- [ParsBERT Github-Ripository](https://github.com/hooshvare/parsbert)

## 🤝 Contribution
Contributions are welcome! Feel free to fork this repository, make improvements, and submit a pull request. If you encounter any issues, create an issue in the GitHub repository.
