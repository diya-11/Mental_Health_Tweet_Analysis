# 🧠 Mental Health Tweet Analysis using PySpark

This project performs sentiment analysis on mental health-related tweets using PySpark and TextBlob in a Google Colab environment.

## 📁 Dataset

- Dataset used: `mental_health_tweets_large.csv`  
- Contains tweets about mental health topics like anxiety, depression, therapy, etc.

## 🔧 Tools & Technologies

- **PySpark** (DataFrame API)
- **UDF** (for sentiment classification)
- **TextBlob** (polarity scoring)
- **Spark SQL**
- **Google Colab**
- **Matplotlib** (for visualizations)

## 📊 Project Workflow

1. Load and explore tweet dataset
2. Preprocess and clean data
3. Use TextBlob to classify tweets into:
   - Positive
   - Negative
   - Neutral
4. Add sentiment as new column using a PySpark UDF
5. Run Spark SQL queries
6. Visualize sentiment distribution using pie and bar charts

## 📈 Sample Output

| Sentiment | Count |
|-----------|-------|
| Positive  | XXX   |
| Negative  | XXX   |
| Neutral   | XXX   |

![Pie Chart Example](your_pie_chart_image_if_you_upload_one)

## 📂 Project Files

- `mental_health_tweet_analysis.ipynb` – Main Colab notebook
- `README.md` – This file

## ✍️ Author

- **Divya Lohar**  
  [LinkedIn](https://www.linkedin.com/in/divya-lohar-40b5251a5) | [GitHub](https://github.com/diya-11)

---

## 📝 Summary

> This project explores how mental health discussions appear on social media. It uses distributed processing with PySpark and NLP techniques to analyze sentiment and visualize patterns in user tweets.


