# Enhancing Sentiment Classification Using Engineered Text Features
*A Case Study on Amazon Food Reviews*

## 🧠 Project Overview

This project explores how engineered sentiment and linguistic features can improve sentiment classification performance in food product reviews. The analysis uses the **Amazon Fine Food Reviews** dataset and compares multiple classification models including **Logistic Regression**, **Random Forest**, and **Naive Bayes**.

Key contributions:
- Advanced feature engineering (polarity, subjectivity, structural cues)
- Rigorous model tuning and cross-validation
- Reproducibility and interpretability

## 📊 Dataset

- **Name**: Amazon Fine Food Reviews  
- **Source**: [Kaggle](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)  
- **Size**: 568,454 reviews from 256,059 users on 74,258 products  

## ⚙️ How to Run

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/sentiment-thesis.git
cd sentiment-thesis
```

### 2. Set up environment
Using pip:
```bash
pip install -r requirements.txt
```

### 3. Run notebooks
Open the notebooks in the `notebooks/` folder using Jupyter Lab or Jupyter Notebook to explore feature engineering and model comparison.

## 🏗️ Models Used

- Logistic Regression
- Random Forest
- Gaussian Naive Bayes

Hyperparameter tuning was done using `GridSearchCV` with 5-fold cross-validation.

## 📈 Results

| Model            | Accuracy | Precision | Recall | F1-score |
|------------------|----------|-----------|--------|----------|
| Random Forest    | 0.88     | 0.90      | 0.97   | **0.93** |
| Logistic Regr.   | 0.87     | 0.87      | 0.98   | 0.92     |
| Naive Bayes      | 0.84     | 0.87      | 0.96   | 0.91     |

Top-N evaluation (N=10) also showed **Random Forest** achieving highest precision and recall.

## 🧪 Feature Engineering

Engineered features include:
- `SentimentText_Polarity`
- `SentimentText_Subjectivity`
- `TextLengthWords`
- `NumUppercaseWords`
- `AvgWordLength`

These are implemented in the `Feature Engineering and EDA.ipynb` notebook.

## 📜 License

MIT License. See [LICENSE](LICENSE) for details.

## 🤝 Acknowledgements

This project was conducted as part of the **MSc Data Science & Society** program at **Tilburg University**.  
Supervisor: Prof. Dr. Eric Postma  
Dataset: McAuley (2012) – Amazon Fine Food Reviews  
Sentiment analysis: TextBlob (Loria, 2018)

## 📬 Contact

For questions, reach out via GitHub Issues or contact me at `r.h.m.vdnborne@tilburguniversity.edu`.
