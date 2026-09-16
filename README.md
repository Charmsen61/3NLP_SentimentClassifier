# Simple Sentiment Classifier

This project is a basic sentiment analysis classifier built using Python.  
It uses a small set of hand‑crafted features and logistic regression to decide  
whether a sentence is positive or negative.

## Features Used
The model extracts the following features from each sentence:

- Count of positive words  
- Count of negative words  
- Whether "!" appears  
- Whether "not" appears  
- Total word count  
- (Optional) Any extra features you add

These features are combined using weights to compute a score, which is passed  
through a sigmoid function to get a probability.

## How It Works
1. The text is tokenized and cleaned.  
2. Features are extracted.  
3. The model computes `z = w·x + b`.  
4. The sigmoid function converts `z` into a probability.  
5. If the probability > 0.5 → **positive**, else → **negative**.


