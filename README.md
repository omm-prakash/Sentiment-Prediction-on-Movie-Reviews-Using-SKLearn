# Sentiment-Prediction-on-Movie-Reviews
In the dataset, each record represents a movie review pair with movie title, description, genres, duration, director, actors, users' ratings, review text, reviewer name, etc. The task is to build an ML model to predict the sentiment of the review text.

In this project, I aim to predict movie reviews' sentiments (positive or negative) using various machine learning algorithms. We provide a set of scripts and Jupyter notebooks to preprocess the data, train models, and evaluate their performance.

## Setup Environment

Creating a Conda environment to manage the required dependencies is recommended to get started with this project. Follow the steps below to set up the environment:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/omm-prakash/Sentiment-Prediction-on-Movie-Reviews.git
   cd Sentiment-Prediction-on-Movie-Reviews
   conda env create mlp -f environment.yml
   ```
2. **Activate the Conda environment**
   ```bash
   conda activate mlp
   jupyter notebook
   ```
## Compition & Project Details

The problem statement was hosted by the IITM team on Kaggle. The link for the competition is [here](https://www.kaggle.com/competitions/sentiment-prediction-on-movie-reviews). 

**The project has the following sections**
    
1. **Data Cleaning**
    - Collecting movies, i.e., available both in train and test data
    - Collecting columns, i.e., required for sentiment analysis from movies,
2. **Feature Engineering**
3. **Data Preprocessing**
4. **Model Training**
    - Dummy Classifier
    - SVM
    - KNN
    - Logistic Regression
    - Decision Tree
    - Bagging
        - DecisionTreeClassifier
        - KNN
    - Boosting
        - Ada Boost
            - DecisionTreeClassifier
            - SGD
        - Gradient Boosting
    - SGD Classifier
    - Perceptron Classifier

## Result
| S No. | Model               | One-Hot Encoding | With Feature Selection | Handling Class Imbalance | Adding Meta Data |
| ----- | ------------------- | ---------------- | ---------------------- | ------------------------ | ---------------- |
| 1     | Logistic Regression | 87.65            | **88.45**                  | 85.56                    | 88.13            |
| 2     | KNN                 | 78.32            | 76.08                  |                          | 80.71                 |
| 3     | SGD Classifier      | 87.71            | 88.38                  | 85.046                   | 81.209           |

The score I have in the tables are `f1-score` of validation data, i.e., a small portion from the training data.

## Conclusion
In conclusion, my journey through Sentiment Prediction on Movie Reviews has been a compelling exploration of the intricate landscape of machine learning.
    
Starting with Data Cleaning, I meticulously sifted through the dataset, ensuring the foundation of our analysis was robust. Feature Engineering followed suit, where I unearthed valuable insights and transformed raw text into meaningful features that illuminated the sentiment-laden context. I dedicated efforts to Data Preprocessing to foster uniformity and readiness, equipping the data for the subsequent Model Training phase. I tuned and fine-tuned various algorithms through rigorous experimentation, seeking the best performers. The culmination of these endeavors led me to discover a model that displayed remarkable prowess in sentiment prediction. Reviewing my Models, I witnessed the algorithms evolve and adapt to the sentiment nuances within the movie reviews.

In the vast sea of sentiment, my model emerges as a steadfast guide, deciphering the sentiments that shape our cinematic experiences. With a resounding F1-score of **0.88458**, I have harnessed the potential of machine learning to contribute to a deeper understanding of human expression in the realm of movie reviews.
