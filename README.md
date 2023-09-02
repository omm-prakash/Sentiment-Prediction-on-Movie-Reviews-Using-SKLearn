# Sentiment-Prediction-on-Movie-Reviews
In the dataset, each record represents a movie review pair with movie title, description, genres, duration, director, actors, users' ratings, review text, reviewer name, etc. The task is to build an ML model to predict the sentiment of the review text.

In this project, I aim to predict movie reviews' sentiments (positive or negative) using various machine learning algorithms. We provide a set of scripts and Jupyter notebooks to preprocess the data, train models, and evaluate their performance.

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
5. **Review Models**
6. **Conclusion**

## Setup Environment

Creating a Conda environment to manage the required dependencies is recommended to get started with this project. Follow the steps below to set up the environment:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/Sentiment-Prediction-on-Movie-Reviews.git
   cd Sentiment-Prediction-on-Movie-Reviews
   conda env create mlp -f environment.yml
   ```
2. **Activate the Conda environment**
   ```bash
   conda activate mlp
   jupyter notebook
   ```

