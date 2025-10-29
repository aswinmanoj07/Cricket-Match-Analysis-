🏏 IPL Match Winner Prediction
📘 Introduction

This project predicts the winner of an IPL (Indian Premier League) cricket match using machine learning.
It uses two datasets — matches.csv and deliveries.csv — which contain information about past IPL matches and ball-by-ball details.
The main goal is to analyze the data, train a model, and predict the winner of a match based on input features like teams, toss, and venue.

🎯 Features

Data cleaning and preprocessing of IPL datasets

Visualization of team performance, toss impact, and venue advantage

Machine learning model to predict the match winner

Step-by-step code with clear output and graphs

🗂️ Files in the Project
IPL_Match_Winner_Prediction/
│
├── ipl code.ipynb       # Jupyter Notebook with full code
├── matches.csv          # IPL match data
├── deliveries.csv       # Ball-by-ball delivery data
└── README.md            # Project documentation

⚙️ How to Run the Project
Step 1: Install Required Libraries

Open your terminal or command prompt and run:

pip install pandas numpy matplotlib seaborn scikit-learn

Step 2: Open the Notebook

Open Jupyter Notebook.

Load the file ipl code.ipynb.

Run all cells one by one.

Step 3: Load the Datasets

Make sure the files matches.csv and deliveries.csv are in the same folder as your notebook.
If not, change the file paths in the code:

matches = pd.read_csv("path/to/matches.csv")
deliveries = pd.read_csv("path/to/deliveries.csv")


Example:

matches = pd.read_csv("C:/Users/Aswin/Documents/matches.csv")
deliveries = pd.read_csv("C:/Users/Aswin/Documents/deliveries.csv")

Step 4: View the Results

After running all cells, you will see:

Cleaned datasets and analysis results

Graphs showing team and toss performance

Model accuracy

A predicted match winner (for example, "Predicted Winner: Mumbai Indians")

📊 What the Project Does

Reads and cleans IPL data

Creates visual graphs and trends

Trains a machine learning model (Random Forest / Logistic Regression)

Predicts which team is likely to win based on given inputs

🔮 Future Improvements

Add player statistics for better predictions

Build a web interface using Streamlit

Try deep learning models for higher accuracy
