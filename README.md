# Exploring Financial Fund Patterns Through Clustering and Machine Learning

## Project Overview
This project utilizes advanced machine learning techniques, specifically clustering and classification, to analyze patterns in financial fund data. By examining metrics such as fund performance, risk levels, and management fees, the project uncovers insights that can inform investment strategies. As a supplementary feature, the project includes a prototype tool for personalized fund recommendations based on user input.

## Objectives
- **Data Collection and Preparation**: Processed financial fund data to clean and structure it for analysis.
- **Feature Analysis**: Explored both numeric and categorical features to understand their impact on clustering outcomes.
- **Clustering and Classification**: Applied KMeans and Hierarchical Clustering to identify patterns and Logistic Regression for predicting cluster membership.
- **Supplementary Recommendation Tool**: Developed a prototype to demonstrate the potential for user-driven fund suggestions.

## Techniques Used
- **Data Preprocessing**: Cleaning missing data, scaling numeric features, and encoding categorical features.
- **Clustering Algorithms**: Applied KMeans and Hierarchical Clustering to segment funds into meaningful groups.
- **Classification Models**: Logistic Regression, SVM, Random Forest, and Decision Trees were evaluated for predicting cluster assignments.
- **Evaluation Metrics**: Used accuracy, precision, recall, and F1-score to evaluate classification performance.
- **Supplementary Tool**: Designed to predict clusters for new data and suggest funds based on user preferences.

## Results
- Key clusters were identified, representing distinct fund profiles, such as high-risk vs. low-risk funds and fee-efficient vs. high-fee funds.
- Logistic Regression achieved the highest accuracy (73%) in classifying cluster memberships, which supports the segmentation process.
- The supplementary recommendation prototype demonstrates potential for tailored fund suggestions based on user-defined criteria.

## Conclusion
This study demonstrates the effectiveness of clustering and classification techniques in uncovering financial fund patterns. The insights derived from the analysis can guide investors in better understanding fund characteristics. The supplementary recommendation tool illustrates one potential application of these insights, with opportunities for future enhancements such as integrating external data or refining the logic.

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
