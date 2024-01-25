# Sentiment-Analysis-On-Amazon-Review

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

