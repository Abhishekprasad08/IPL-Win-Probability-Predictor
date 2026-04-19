IPL Win Probability Predictor

This project is a Machine Learning-based IPL match win predictor built
using Streamlit. It predicts the probability of a team winning during a
live match based on current match conditions.

Features: - Predicts win probability in real-time - Interactive UI using
Streamlit - Inputs include batting team, bowling team, city, target,
score, overs, wickets - Displays winning chances for both teams

How It Works: The model calculates: - Runs left - Balls left - Remaining
wickets - Current Run Rate (CRR) - Required Run Rate (RRR)

These are passed into a trained ML pipeline (pipe.pkl) to predict win
probabilities.

Project Structure: - app.py (Streamlit app) - pipe.pkl (trained model) -
IPL Prediction.ipynb (model training) - README.txt

Installation: 1. Clone the repo 2. Install dependencies using: pip
install -r requirements.txt 3. Run: streamlit run app.py

Usage: - Select teams and city - Enter match details - Click Predict
Probability

Notes: - Predictions are based on historical data - Accuracy may vary -
Avoid zero overs input

Future Improvements: - Add player stats - Improve UI - Deploy online

Author: Abhishek Prasad
