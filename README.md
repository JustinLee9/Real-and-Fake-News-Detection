# Fake News Detection

Machine learning model that identifies fake news articles with 100% accuracy.

## What it does

Takes a news article and predicts if it's real or fake based on the title, content, and topic.

## Dataset

- 44,898 news articles from Kaggle
- Half real news, half fake news
- Includes title, text, subject, and date

## Results

**Best Model**: Logistic Regression
- **Accuracy**: 100%
- **Speed**: Fast training and prediction

## Key Findings

- Fake news titles are longer than real news titles
- Article topic strongly predicts if news is fake
- Text content patterns differ between real and fake articles

## Real-world uses

- Social media content filtering
- News website quality control
- Fact-checking tools

---

*Built with Python, scikit-learn, and TF-IDF text processing*
