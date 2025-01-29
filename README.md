# Spotify-Music-Recommendation-System

## Overview
This project develops a music recommendation system for Spotify using **Support Vector Machine (SVM)** and **Random Forest** algorithms. The goal is to predict song popularity based on attributes such as danceability, energy, tempo, and valence.

## Dataset
The dataset used is the **Spotify Tracks dataset from Kaggle**, containing features like:
- Danceability
- Energy
- Tempo
- Valence
- Speechiness
- Acousticness
- Popularity (Target Variable)

## Project Structure
- `spotify_recommendation.py`: Main script for data preprocessing, model training, and evaluation.
- `spotify_tracks.csv`: Dataset file (ensure it's in the same directory before running the script).
- `svm_model.pkl` & `rf_model.pkl`: Saved models for later use.
- `README.md`: Project documentation.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/spotify-recommendation.git
   cd spotify-recommendation
   ```
2. Install dependencies:
   ```bash
   pip install pandas scikit-learn joblib
   ```

## Usage
1. Ensure `spotify_tracks.csv` is in the directory.
2. Run the script:
   ```bash
   python spotify_recommendation.py
   ```
3. View accuracy results for SVM and Random Forest models.

## Results
- **SVM Accuracy:** ~85.59%
- **Random Forest Accuracy:** ~81.04%

## Future Improvements
- Enhance the feature selection process.
- Incorporate deep learning techniques for better recommendations.
- Extend recommendations beyond just song popularity.

## Contributors
- **Group 11:** Ranendra Boompelly, Umanath Boyapathi, Lawrence Cantrell, Navya Tirukkovalluri

## License
This project is licensed under the MIT License.

