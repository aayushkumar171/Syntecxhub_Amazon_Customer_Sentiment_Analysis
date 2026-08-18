# 🛒 Amazon Customers Sentiment Analysis 

A Natural Language Processing (NLP) project that analyzes Amazon product reviews to classify customer sentiment (positive, negative, neutral) and surface actionable insights for product improvement and customer satisfaction.

## 🎯 Objective
Analyze a dataset of Amazon product reviews to clean and preprocess the review text, classify sentiment, identify patterns in customer feedback and ratings, and generate insights that support product improvement decisions.

## ✅ Project Tasks
- Analyze Amazon product reviews dataset
- Clean and preprocess review text data
- Perform sentiment classification (positive, negative, neutral)
- Identify patterns in customer feedback and ratings
- Visualize sentiment distribution and trends
- Generate insights for product improvement and customer satisfaction

```

## 🛠️ Tools & Technologies
- **Python** (pandas, numpy) — data handling
- **NLP** (nltk / textblob / vaderSentiment / scikit-learn) — text preprocessing & sentiment classification
- **matplotlib, seaborn, wordcloud** — visualization of sentiment distribution and trends
- **Jupyter Notebook** — end-to-end analysis workflow

> This project was built entirely in Python — no Power BI/Tableau dashboard was used; all visuals are generated within the notebook.

## 🔍 Workflow
1. **Import Libraries & Load Raw Reviews Dataset**
2. **Text Preprocessing** — lowercasing, removing punctuation/stopwords/special characters, tokenization, lemmatization
3. **Sentiment Classification** — label each review as positive, negative, or neutral (lexicon-based or ML-based approach)
4. **Feedback & Rating Pattern Analysis** — compare sentiment against star ratings, review length, and product categories
5. **Visualization** — sentiment distribution charts, trend over time, word clouds for positive vs. negative reviews, most frequent complaint/praise terms
6. **Insight Generation** — key takeaways on product strengths, recurring complaints, and recommendations for improving customer satisfaction

## 📈 Key Outputs
- Sentiment distribution (positive / negative / neutral breakdown)
- Sentiment trends over time
- Word clouds highlighting common themes in positive vs. negative reviews
- Correlation between star ratings and predicted sentiment
- Summary of actionable insights for product improvement

## 🚀 How to Run
1. Clone the repo
   ```bash
   git clone https://github.com/<your-username>/amazon-sentiment-analysis.git
   cd amazon-sentiment-analysis
   ```
2. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```
3. Open `Jupyter_Notebook/Amazon Customer Sentiment Analysis.ipynb` in Jupyter Notebook / JupyterLab and run the cells

## 📌 Notes
- Update the raw data source path in the notebook if you re-run it with your own dataset.
- If using NLTK, you may need to download additional resources on first run, e.g.:
  ```python
  import nltk
  nltk.download('stopwords')
  nltk.download('punkt')
  nltk.download('wordnet')
  ```
