# Review Sentiment Analyzer

A Python-based Text & Speech Analysis mini-project that analyzes written reviews and classifies them as **Positive, Negative, or Neutral**.

## Objective

The objective of this project is to determine the sentiment expressed in a piece of text by analyzing its polarity and subjectivity.

## Features

- Accepts user-written reviews
- Cleans and preprocesses text
- Calculates sentiment polarity
- Calculates subjectivity
- Classifies text as Positive, Negative, or Neutral
- Includes multiple test cases
- Displays sentiment distribution using a chart

## Technologies Used

- Python
- TextBlob
- Pandas
- Matplotlib
- Regular Expressions

## NLP Technique

The project uses **sentiment analysis** based on TextBlob's polarity score.

- Polarity > 0.1 → Positive
- Polarity < -0.1 → Negative
- Otherwise → Neutral

## How It Works

1. User enters a review.
2. The text is cleaned.
3. TextBlob analyzes the sentence.
4. Polarity and subjectivity are calculated.
5. The application assigns a sentiment category.
6. Results are displayed to the user.

## Example

**Input:**

> The product is excellent and I really enjoyed using it.

**Output:**

```text
Sentiment: Positive
Polarity: 0.8
Subjectivity: 0.75
```

## Requirements

```bash
pip install textblob pandas matplotlib
```

## Running the Project

Open `Sentiment_Analysis.ipynb` in:

- Google Colab
- Jupyter Notebook
- VS Code

Run the cells in order and uncomment the application function when you want interactive input.

## Project Structure

```text
Sentiment-Analysis/
│
├── Sentiment_Analysis.ipynb
└── README.md
```

## Applications

- Product review analysis
- Customer feedback analysis
- Movie review analysis
- Social media opinion analysis
- Survey analysis

## Conclusion

This project demonstrates how Natural Language Processing can be used to automatically understand the emotional polarity of written reviews.
