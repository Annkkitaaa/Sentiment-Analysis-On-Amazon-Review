# Sentiment-Analysis-On-Amazon-Review
This project implements a sentiment analysis model for Amazon Alexa reviews using machine learning algorithms and provides a Flask API for making predictions.

## Overview

The sentiment analysis model analyzes Amazon Alexa reviews to predict whether they convey positive or negative sentiments. The project contains code for data exploration, model training, and a Flask API for making predictions.

## Folder Structure

- `Data/`: Contains the necessary data file (`amazon_alexa_reviews.csv`) for training and testing the sentiment analysis model.
- `Models/`: Contains pre-trained models stored as pickle files:
  - `decision_tree_model.pkl`: Decision tree model.
  - `random_forest_model.pkl`: Random forest model.
  - `xgboost_model.pkl`: XGBoost model.
- `countvectorizer.pkl`: CountVectorizer file used for text vectorization.
- `notebooks/`: Contains Jupyter notebooks for data exploration and model training.
- `api.py`: Flask application code for the sentiment analysis API.


## How to Run

Follow these steps to set up and run the Amazon Alexa Reviews Analyzer:

### Step 1: Clone the Repository

```bash
git clone https://github.com/Annkkitaaa/Sentiment-Analysis-On-Amazon-Review.git
```

### Step 2: Create and Activate a Conda Environment

Navigate to the cloned repository and create a new conda environment:

```bash
conda create -n amazonreview python=3.10
```

Activate the newly created environment:

```bash
conda activate amazonreview
```

### Step 3: Install Requirements

Install the required Python packages by running:

```bash
pip install -r requirements.txt
```

### Step 4: Run the App

Execute the following command to run the application:

```bash
flask --app api.py run
```

### Step 5: Access the App

The application will run on port 5000. Open your web browser and visit:

[http://localhost:5000](http://localhost:5000)

You should now have the Amazon Alexa Reviews Analyzer up and running locally on your machine. Feel free to explore the functionality of the app and analyze Alexa reviews.

