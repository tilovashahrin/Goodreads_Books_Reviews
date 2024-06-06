# Goodreads_Books_Reviews

## Overview
This Jupyter Notebook provides a comprehensive analysis of over 1.3 million book reviews from Goodreads. The dataset includes reviews for 25,475 books by 18,892 users. Our primary objective is to perform sentiment analysis on these reviews, classifying them as positive, negative, or neutral. We utilize various machine learning algorithms, including Decision Tree, Random Forest, and XGBoost, to achieve this goal.

## Dataset Description
### Files
- **goodreads_train.csv:** The training set containing book reviews data.
- **goodreads_test.csv:** The test set containing book reviews data.
- **goodreads_sample_submission.csv:** Sample submission file for predictions.

### Columns
1. **user_id:** Unique identifier for the user.
2. **book_id:** Unique identifier for the book.
3. **review_id:** Unique identifier for the review.
4. **rating:** Rating given by the user, ranging from 0 to 5.
5. **review_text:** Text of the review provided by the user.
6. **date_added:** Date when the review was added.
7. **date_updated:** Date when the review was last updated.
8. **read_at:** Date when the user finished reading the book.
9. **started_at:** Date when the user started reading the book.
10. **n_votes:** Number of votes received on the review.
11. **n_comments:** Number of comments received on the review.

This dataset provides comprehensive information about book reviews, including user ratings, review text, dates of review addition and update, reading status, and interaction metrics such as votes and comments. It serves as a valuable resource for sentiment analysis, user behavior analysis, and recommendation system development within the Goodreads platform.

## How to Use This Notebook
Clone the repository: Download or clone the repository containing this notebook and the dataset.
Install dependencies: Ensure all required libraries are installed. See the Dependencies section below.
Run the notebook: Open the notebook and execute the cells sequentially.

## How to Use This Notebook

### Clone the Repository
1. Download or clone the repository containing this notebook and the dataset.

```bash
git clone <repository_url>
```

### Install Dependencies
2. Ensure all required libraries are installed. You can install these dependencies using pip:

```bash
pip install numpy pandas scikit-learn xgboost matplotlib seaborn
```

### Run the Notebook
3. Open the notebook using Jupyter Notebook or JupyterLab and execute the cells sequentially. This notebook contains sections for data loading, preprocessing, model training, evaluation, and result analysis. Follow the instructions and execute each cell to observe the results and insights from the analysis.

