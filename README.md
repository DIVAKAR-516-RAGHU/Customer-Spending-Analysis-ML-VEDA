# Customer Spending Analysis and Prediction Using Machine Learning

## Project Overview

This project was developed as part of the AVEDA Technology internship program. It focuses on analyzing customer spending behavior, segmenting customers based on annual income and spending scores, and building a machine learning model to estimate customer spending scores.

The project demonstrates a basic end-to-end machine learning workflow, including data preprocessing, exploratory data analysis, customer segmentation, model training, performance evaluation, and result visualization.

## Objectives

- Segment customers based on annual income and spending score.
- Visualize customer groups using scatter plots and count plots.
- Analyze characteristics of different customer segments.
- Train a Random Forest regression model to predict spending scores.
- Evaluate model performance using regression metrics.
- Analyze individual prediction errors.
- Generate business insights and export results.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset

The project uses the Mall Customers dataset, containing 200 customer records.

**Features include:**
- Customer ID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

Dataset source: [Mall Customers Dataset](https://raw.githubusercontent.com/MahimaSriK/Mall-Customer-Segmentation-Dataset/main/Mall_Customers.csv)

## Project Workflow

1. **Data Loading:** Import the dataset using Pandas.
2. **Data Preprocessing:** Standardize column names and prepare the required features.
3. **Customer Segmentation:** Divide customers into four groups using median annual income and spending score.
4. **Exploratory Data Analysis:** Visualize income, spending scores, and segment distributions.
5. **Business Insights:** Generate marketing recommendations for each segment.
6. **Model Training:** Train a Random Forest regression model using age and annual income to estimate spending scores.
7. **Model Evaluation:** Calculate Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² score.
8. **Error Analysis:** Compare actual and predicted scores and examine individual prediction errors.
9. **Result Export:** Save customer segmentation and segment analysis results as CSV files.

## Customer Segmentation

Customers are categorized into four groups:

| Segment | Business Strategy |
|---|---|
| High Income – High Spending | Premium products and loyalty rewards |
| High Income – Low Spending | Personalized offers and targeted promotions |
| Low Income – High Spending | Affordable bundles and relevant discounts |
| Low Income – Low Spending | Budget-friendly promotions and engagement campaigns |

## Machine Learning Model

A Random Forest Regressor from Scikit-learn is trained to estimate customer spending scores using age and annual income.

The model is evaluated using:

- **MAE:** Average absolute prediction error.
- **MSE:** Average squared prediction error.
- **RMSE:** Prediction error expressed in the target's units.
- **R² Score:** Measures how well the model explains variation in the target values.

The model is a baseline experiment and does not guarantee accurate predictions for future customer behavior.

## Output Files

- `customer_spending_segments.csv` — Customer records with assigned segments.
- `customer_segment_analysis.csv` — Customer counts and average income and spending scores by segment.

## How to Run

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. Open the project notebook in Jupyter Notebook.
4. Run the cells sequentially to reproduce the analysis, train the model, evaluate its performance, and generate the output files.

## Learning Outcomes

- Data cleaning and preprocessing
- Exploratory data analysis and visualization
- Rule-based customer segmentation
- Regression model training and evaluation
- Prediction-error analysis
- Business insight generation
- Exporting analytical results

## Internship

**Organization:** AVEDA Technology  
**Program:** Internship Program  
**Day:** 33 of 45  
**Project:** Advanced Customer Spending Analysis

## Author

**Divakar R**  
B.E. Electronics and Communication Engineering  
Adithya Institute of Technology, Coimbatore

---

*This project was created for educational and internship learning purposes.*
