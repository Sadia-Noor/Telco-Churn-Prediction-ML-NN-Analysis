# Telecom Churn Analysis: ML & NN Approach

## Overview
This project explores the phenomenon of customer churn in the telecommunications industry using machine learning (ML) and neural network (NN) techniques. By analyzing a large-scale dataset from IBM, we aimed to understand the factors contributing to customer churn and develop predictive models to anticipate it. The project includes preprocessing, exploratory data analysis (EDA), model selection and training, and the implementation of advanced techniques like SMOTE-ENN for addressing class imbalance.

## Project Structure
- **Data**: Contains the dataset used for analysis (`telco_dataset.csv`).
- **Notebooks**: Jupyter notebooks detailing each stage of the project:
  - `01_Data_Preprocessing.ipynb`: Data cleaning and preprocessing.
  - `02_Exploratory_Data_Analysis.ipynb`: EDA to understand the dataset and identify churn patterns.
  - `03_Model_Selection_and_Training.ipynb`: Model selection, training, evaluation, and comparison.
  - `04_Neural_Network_Analysis.ipynb`: Implementation of neural network techniques for churn prediction.
- **Results**: Contains result summaries, visualizations, and performance metrics.
- **README.md**: Overview of the project, instructions, and setup guidelines.

## Getting Started
1. Clone this repository to your local machine.
2. Ensure you have Python and Jupyter Notebook installed.
3. Install the required dependencies by running `pip install -r requirements.txt`.
4. Navigate to the `Notebooks` directory and start exploring the Jupyter notebooks.

## Data
The dataset used in this project contains 7043 instances and 21 attributes, covering various aspects of customer demographics, services, and tenure. It includes information on churn status, services subscribed to, account details, and demographic information.

## Analysis Highlights
- Preprocessing: Converted categorical variables, handled missing values, and performed feature engineering.
- EDA: Visualized churn distribution, explored relationships between features, and identified key insights.
- Model Selection: Trained Logistic Regression, Random Forest, Gradient Boosting, and Decision Tree classifiers.
- Advanced Techniques: Implemented SMOTE-ENN to address class imbalance and improve model performance.
- Neural Network Analysis: Utilized neural network architectures, including LSTM, for enhanced churn prediction.

## Results and Recommendations
- Logistic Regression and Random Forest achieved the highest accuracy, followed by Decision Tree and Gradient Boosting.
- SMOTE-ENN technique significantly improved model performance, particularly in addressing class imbalance.
- Neural network models, especially LSTM, demonstrated promising results, indicating the potential for further exploration.
- Recommendations for telecom companies include implementing long-term contracts, enhancing online security and tech support services, and optimizing service offerings to improve customer retention.

## Future Work
- Incorporate state-of-the-art predictive models and customer feedback analysis for deeper insights.
- Explore additional features and data sources to enhance churn prediction accuracy.
- Continuously refine models and strategies based on evolving customer behavior and industry trends.
