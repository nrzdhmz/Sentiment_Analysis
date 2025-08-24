# Amazon Fine Food Reviews Sentiment Analysis

Analyze Amazon food reviews using **VADER** and **RoBERTa** sentiment models.

## Dataset
- **[Amazon Fine Food Reviews](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)** (`Reviews.csv`)
- Columns include `Id`, `Score`, `Text`, etc.

## Libraries
`pandas`, `numpy`, `matplotlib`, `seaborn`, `nltk`, `transformers`, `tqdm`

## Features
- Visualize star ratings
- Tokenize text and POS tagging
- Sentiment analysis with VADER & RoBERTa
- Compare sentiment scores vs. star ratings

## Example
```python
import pandas as pd
import nltk
from transformers import AutoTokenizer, AutoModelForSequenceClassification, pipeline

df = pd.read_csv('./Reviews.csv')
sia = nltk.sentiment.SentimentIntensityAnalyzer()
sia.polarity_scores("This product is amazing!")
```

