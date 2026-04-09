# Amazon Review Score Prediction (NLP & Regression)

This project was completed as part of graduate coursework in Business Analytics and AI at Northern Illinois University. It builds on prior NLP analysis to predict Amazon review scores using text data and regression models.

## Overview
- Analyzed large-scale Amazon review data (500K+ reviews)  
- Applied natural language processing (NLP) techniques to transform unstructured text into model-ready features  
- Built regression models to predict customer review scores  
- Compared model performance against a baseline approach  

## NLP & Feature Engineering
- Combined review summary and text into a single feature  
- Applied TF-IDF vectorization to convert text into numerical features  
- Engineered additional features including review length and helpfulness ratio  
- Processed and prepared data for use in predictive modeling  

## Modeling Approach
- Established a baseline model using mean prediction  
- Built and evaluated:
  - Linear Regression  
  - Ridge Regression  
- Split data into training and testing sets for model evaluation  

## Evaluation Metrics
- Mean Absolute Error (MAE)  
- Root Mean Squared Error (RMSE)  
- R² Score  

## Key Insights
- Both regression models improved performance compared to the baseline model  
- Ridge regression performed best overall, showing lower error (MAE and RMSE) and higher R² compared to linear regression  
- Results indicate that NLP-derived text features provide meaningful predictive signal for customer ratings  

## Data Source
- [Amazon Fine Food Reviews Dataset](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)  
Note: Dataset is not included due to file size.

## Running the Code
To run this project locally, update the file path in the code to match where the dataset is stored on your machine.

## Files in this Repository
- `.ipynb` → full notebook with analysis and modeling  
- `.py` → Python script version of the project  

## Outcome
This project demonstrates the ability to extend exploratory NLP analysis into predictive modeling by applying regression techniques to real-world text data and evaluating model performance using standard metrics.
