# Book Review Sentiment Analysis

This project demonstrates the full machine learning lifecycle for a natural language processing (NLP) classification task. The goal is to predict whether a book review is **positive** or **negative** based on raw text.

---

## Project Overview

- **Problem Type**: Supervised **binary classification** (text sentiment analysis).
- **Business Value**: Real-time monitoring of customer feedback can help product teams identify reputation risks and highlight strengths that drive retention.
- **Input Features**: Raw review text, cleaned and vectorized using **TF-IDF**.
- **Label**: `Positive Review` (1 = positive, 0 = negative).
- **Models Compared**:
  - Logistic Regression (with hyperparameter tuning)
  - Feedforward Neural Network (Keras)
- **Key Metrics**: Accuracy, Precision, Recall, F1 Score, and Confusion Matrix.

---

## Dataset

- **Expected Format**: A CSV file with the following columns:
  - `Review`: The text of the book review.
  - `Positive Review`: Binary label (1 = positive, 0 = negative).
- **Default Path**: Place the dataset as `bookReviewsData.csv` in the project root, or set the `DATA_PATH` environment variable to the dataset's location.

---

## Environment Setup

### Prerequisites

- Python 3.x
- Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `tensorflow`, `keras`

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Book-Review-Sentiment-Analysis.git
   cd Book-Review-Sentiment-Analysis
