# K-Nearest Neighbors (KNN) Classifier on Iris Dataset
This project demonstrates binary classification using the K-Nearest Neighbors (KNN) algorithm on a filtered version of the classic Iris dataset. By excluding the "Setosa" class, we focus on distinguishing Versicolor and Virginica species using their sepal and petal measurements.

# Project Highlights
### Goal: Classify Iris species (0: Versicolor, 1: Virginica)

### Data Preprocessing: Removed "Setosa", encoded labels

### Train/Test Split: 75/25 ratio with fixed random seed

### Model: KNN Classifier (default n_neighbors=3)

### Performance: Evaluated using accuracy and classification report

### Hyperparameter Tuning (Optional): GridSearchCV to find best k

# Tech Stack
Python

pandas

seaborn

scikit-learn

numpy

Google Colab (recommended for execution)

# Run it Yourself
Clone the repository:

bash
git clone https://github.com/your-username/your-repo-name.git
Open the notebook in Google Colab or run locally.

Install dependencies:

bash
pip install pandas numpy seaborn scikit-learn
Follow the notebook to replicate results.

# Results
Achieved high classification accuracy

Precision, recall, and F1 scores show balanced class performance
