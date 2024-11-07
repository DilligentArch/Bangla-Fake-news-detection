# Bangla Fake News Detection

This project aims to detect fake news articles in the Bangla language using machine learning techniques. By classifying articles as **Fake** or **Real**, this tool helps tackle misinformation and enhance media credibility in the Bangla-speaking community.

## Project Overview

Fake news detection is essential to counter misinformation and maintain trust in media. This project applies **natural language processing (NLP)** and **machine learning** to analyze Bangla news articles. It provides a structured approach to detecting fake news, covering data preprocessing, model training, and evaluation.

## Features

- **Binary Classification**: Classifies Bangla news articles as either "Fake" or "Real."
- **Data Processing**: Preprocesses Bangla text data efficiently for feature extraction.
- **Model Evaluation**: Uses metrics to assess model performance, such as accuracy and F1-score.
- **Exploratory Data Analysis (EDA)**: Visualizes insights about the dataset distribution and patterns.


## Requirements
- Python 3.x
- Jupyter Notebook
- pandas, numpy, sklearn, nltk (for text preprocessing)
- matplotlib, seaborn (for visualizations)

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/username/Bangla-Fake-News-Detection.git
     cd Bangla-Fake-News-Detection
     pip install -r requirements.txt


## Dataset
The dataset consists of labeled Bangla news articles, where each article is marked as either "Fake" or "Real." Ensure the dataset is placed in the data/ folder.

## Usage
- Open Bangla Fake News Detection.ipynb in Jupyter Notebook.
- Run each cell step-by-step to perform data preprocessing, model training, and evaluation.
- Modify parameters if needed to experiment with different models or techniques.

## Dataset Preview
![image](https://github.com/user-attachments/assets/a4eb75ab-ab8e-4ed6-b61f-39714fb3016f) 
![image](https://github.com/user-attachments/assets/c421d0c9-3e71-4af2-9d90-0a09c34cc446)



## Data Distribution Visualization
 **Before Balancing**
 ![image](https://github.com/user-attachments/assets/14be2a1d-ba39-4636-990d-c89320680dca)

 **After Balancing**
 ![image](https://github.com/user-attachments/assets/006b9bf8-d68c-4bbd-b11f-4d1683e90d0f)



## Model Performance Metrics
![image](https://github.com/user-attachments/assets/e89fcab8-85de-43c3-8edc-d9f5a5ec4672)


## Confusion Matrix
![image](https://github.com/user-attachments/assets/911bc3e2-7ce3-4e36-8964-30ece8aaee22)

## ROC Curve
![image](https://github.com/user-attachments/assets/c6458d19-8851-4d18-8f5d-5cd4d66a0eeb)

## Sample Predictions
![image](https://github.com/user-attachments/assets/8c4a8756-71bd-434d-b7ec-e8608dd29bdd)


## Models
This project includes several machine learning models for binary classification, such as:

- Logistic Regression
- Decision Trees
- Random Forest
- Support Vector Machines (SVM)
## Evaluation
The models are evaluated using standard metrics like accuracy, precision, recall, and F1-score to assess their performance in detecting fake news.

## Results
Model performance metrics and results are discussed in the notebook. Key insights from EDA and model evaluation are summarized with visual aids.

Contributing
Contributions are welcome! Please fork this repository and submit a pull request with improvements or additional features.
