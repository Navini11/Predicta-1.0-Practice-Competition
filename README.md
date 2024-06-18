# 🍰 Bakery Shop Sales Prediction Challenge

Welcome to our repository for the Bakery Shop Sales Prediction Challenge, a practice competition for Predicta 1.0 organized by the IEEE Student Branch, University of Peradeniya. This competition aims to test and improve our forecasting skills by predicting daily sales quantities of various bakery items across three different outlets. 

## 📋 Overview

### 🎯 Competition Goal
In the food industry, accurately predicting product demand is crucial for maintaining efficiency and ensuring freshness. Our task is to forecast the daily sales quantities of bakery items from June 1st to June 14th, 2024, using historical sales data from January 1st to May 31st, 2024.

### 📊 Data Description

- **historical_data.csv**: Contains historical sales data with the following columns:
  - `transaction_id`: Unique identifier for each transaction
  - `transaction_date`: Date of the transaction
  - `transaction_time`: Time of the transaction
  - `transaction_qty`: Quantity of items sold in the transaction
  - `store_id`: Identifier for the store where the transaction occurred
  - `product_id`: Identifier for the product sold
  - `unit_price`: Price per unit of the product

- **product_descriptions.csv**: Contains descriptions of the products with the following columns:
  - `product_id`: Identifier for the product
  - `product_category`: Category of the product (e.g., Pastries, Cakes)
  - `product_type`: Type of the product (e.g., Croissants, Muffins)
  - `product_detail`: Detailed description of the product

- **submission_key.csv**: Template for our submission with the following columns:
  - `ID`: ID assigned for the respective date, shop, and product combination
  - `transaction_date`: Date for which the sales quantity is predicted
  - `store_id`: Identifier for the store
  - `product_id`: Identifier for the product

- **submission_format.csv**: Submission format with the following columns:
  - `ID`: ID assigned for the respective date, shop, and product combination
  - `sold_qty`: Quantity of items sold (to be filled by participants)

### 🏆 Evaluation
Submissions are evaluated based on the Root Mean Squared Error (RMSE) between the predicted sold quantities and the actual sold quantities.

## 👥 Team Members
- Member 1: [Akhila Prabodha]
- Member 2: [Navini Jagoda]
- Member 3: [Janindu Shehan]

## 🚀 Getting Started

### 📋 Prerequisites
- Python 3.x
- Jupyter Notebook
- Required Python libraries (see `requirements.txt`)

### 🛠 Installation
Clone the repository and install the required packages:

```sh
git clone https://github.com/yourusername/bakery-sales-prediction.git
cd bakery-sales-prediction
pip install -r requirements.txt
```

### 📝 Usage
1. **Data Analysis**: Explore the data using `notebooks/data_analysis.ipynb`.
2. **Feature Engineering**: Create new features in `notebooks/feature_engineering.ipynb`.
3. **Model Training**: Train your predictive models in `notebooks/model_training.ipynb`.
4. **Model Evaluation**: Evaluate model performance in `notebooks/model_evaluation.ipynb`.
5. **Prediction**: Generate predictions using `src/predict.py` and create the final submission file.

### 📤 Submissions
Submit the `final_submission.csv` file located in the `submissions/` directory.

## 🙏 Acknowledgements
We would like to thank the IEEE Student Branch, University of Peradeniya for organizing this competition and providing us with the opportunity to enhance our forecasting skills.

