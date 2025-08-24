# Amazon Fine Food Reviews Sentiment Analysis

Analyze Amazon food reviews using **VADER** and **RoBERTa** sentiment models.

## Dataset
- **[Amazon Fine Food Reviews](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)** (`Reviews.csv`)
- Columns: `Id`, `ProductId`, `UserId`, `ProfileName`, `HelpfulnessNumerator`, `HelpfulnessDenominator`, `Score`, `Time`, `Summary`, `Text`

## Libraries
`pandas`, `numpy`, `matplotlib`, `seaborn`, `nltk`, `transformers`, `tqdm`

## Features
- Visualize star ratings
- Tokenize text and POS tagging
- Sentiment analysis with VADER & RoBERTa
- Compare sentiment scores vs. star ratings

