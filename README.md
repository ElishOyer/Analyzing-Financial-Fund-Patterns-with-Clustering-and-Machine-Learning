# Exploring Financial Fund Patterns Through Clustering and Machine Learning

## Project Overview
This project utilizes advanced machine learning techniques, specifically clustering and classification, to analyze patterns in financial fund data. By examining metrics such as fund performance, risk levels, and management fees, the project aims to uncover insights that can inform investment strategies and provide personalized fund recommendations.

## Objectives
- **Data Collection and Preparation**: Processed financial fund data to clean and structure it for analysis.
- **Feature Analysis**: Explored both numeric and categorical features to understand their impact on clustering outcomes.
- **Clustering and Classification**: Applied KMeans and Hierarchical Clustering to identify patterns and Logistic Regression for predicting cluster membership.
- **Recommendation System**: Built a prototype system that recommends financial funds based on user input preferences.

## Techniques Used
- **Data Preprocessing**: Cleaning missing data, scaling numeric features, and encoding categorical features.
- **Clustering Algorithms**: Applied KMeans and Hierarchical Clustering to segment funds into meaningful groups.
- **Classification Models**: Logistic Regression, SVM, Random Forest, and Decision Trees were evaluated for predicting cluster assignments.
- **Evaluation Metrics**: Used accuracy, precision, recall, and F1-score to evaluate classification performance.
- **Recommendation System**: Designed to predict clusters for new data and recommend funds based on user-specified preferences.

## Results
- The project identified key clusters that represent distinct fund profiles, such as high-risk vs. low-risk funds and fee-efficient vs. high-fee funds.
- Logistic Regression achieved the highest accuracy (73%) in classifying cluster memberships, making it the core model for the recommendation system.
- The recommendation system prototype provides dynamic suggestions tailored to user inputs like risk tolerance, management fees, and fund size.

## Conclusion
This study demonstrates the effectiveness of clustering and classification techniques in uncovering financial fund patterns. The prototype recommendation system illustrates how data-driven insights can guide investors in selecting suitable funds. Future enhancements could involve refining the recommendation logic and incorporating additional external data.

## Installation
To run this project, ensure you have the following Python packages installed:
- `numpy`
- `pandas`
- `sklearn`
- `matplotlib`
- `seaborn`

You can install the required packages using pip:
```bash
pip install numpy pandas scikit-learn matplotlib seaborn

