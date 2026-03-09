# Machine-Learning-Final-Project
🍺 U.S. Craft Beer Regional Identity — Machine Learning Project

This project applies machine learning to identify the geographic region of U.S. craft beers based on their chemical profiles and style information. The goal is to uncover whether measurable product attributes reflect regional brewing identity and market structure.

📂 Dataset

Source: Kaggle

Dataset Name: Craft Cans

Link: https://www.kaggle.com/datasets/nickhould/craft-cans

Dataset Contents

Beers dataset: Product-level information (ABV, IBU, style, brewery ID)

Breweries dataset: Brewery metadata and geographic location

Dataset Size

2,410 beers

558 breweries

⚙️ Requirements

This project was developed using Google Colab with Python.

Python Version

Python 3.10+

Main Libraries

Install dependencies with:

pip install pandas numpy matplotlib seaborn scikit-learn nltk

Libraries Used
pandas — data manipulation
numpy — numerical operations
matplotlib — visualization
seaborn — statistical visualization
scikit-learn — machine learning models & evaluation
nltk — text preprocessing
scipy — sparse matrix operations

▶️ How to Run the Project
Option 1 — Google Colab (Recommended)
Open Google Colab
Upload the notebook:
Download datasets from Kaggle:
beers.csv
breweries.csv
Upload both CSV files into the Colab session
Run all cells from top to bottom

Option 2 — Local Environment
Clone the repository:

git clone <your-repo-link>
cd <repo-folder>

Install dependencies:

pip install -r requirements.txt

Place dataset files in:
/data
  ├── beers.csv
  └── breweries.csv

Run the notebook:
jupyter notebook

🧠 Project Pipeline

Data Collection — Load beer and brewery datasets
Preprocessing — Cleaning, missing values, encoding, scaling
EDA — Regional distribution, ABV/IBU analysis, style trends
Feature Engineering
- Numerical features (ABV, IBU)
Categorical encoding
- TF-IDF vectorization for beer styles
Modeling
- Random Forest (structured data)
- TF-IDF–based text modeling
Evaluation
- Accuracy
- F1-score

🎯 Prediction Task
Objective:
Predict a beer’s geographic region using:
Chemical profile (ABV, IBU)
Beer style information
Text-derived style features (TF-IDF)
Task Type: Multi-class classification

📊 Outputs
Model performance comparison
Feature importance analysis
Regional pattern insights
Visualizations of beer characteristics and geography

👤 Author
Machine Learning Final Project
(Data Science & AI)
