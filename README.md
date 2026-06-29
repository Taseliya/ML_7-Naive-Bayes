
 ML_7 - Naive Bayes (SMS Spam Classification)
 Overview
In this work, we implement a Naive Bayes Classifier to detect spam messages in SMS Spam Collection Dataset.
No libraries were used during model building. We focused on learning the basics of probability, text processing, and Laplace smoothing.

Key Features
- Text preprocessing (punctuation removal + lowercasing)
- Vocabulary creation manually
- Implementation of Multinomial Naive Bayes with Laplace Smoothing
- Classification into spam and ham categories
- 98.21% accuracy achieved on test set

 Dataset
- SMS Spam Collection Dataset
- Number of total instances: 5,572
- Classes: `ham` (0), `spam` (1)
- Train/test split: 80%/20%

 Technologies Used
- Google Colab + Python
- Pandas, NumPy, Matplotlib
- Google Drive (for data access)

 Project Structure
1. Loading Data & Cleaning – Removal of unnecessary columns + feature names change
2. Text Processing – Vocabulary creation (8,355 unique tokens)
3. Probabilities Calculation – Word frequencies counting (for spam/ham)
4. Classifier Building – Using log probabilities + Laplace smoothing
5. Testing

 Results
-Accuracy on test set: 98.21%
- Number of test samples: 1,115
- Number of correct predictions: 1,095
