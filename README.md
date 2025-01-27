# eCommerce Data Science Assignment

This repository contains the code and deliverables for the eCommerce Data Science Assignment. The assignment consists of three tasks:
1. **Exploratory Data Analysis (EDA) and Business Insights**
2. **Lookalike Model**
3. **Customer Segmentation / Clustering**

## Table of Contents
- [Overview](#overview)
- [Task 1: Exploratory Data Analysis and Business Insights](#task-1-exploratory-data-analysis-and-business-insights)
- [Task 2: Lookalike Model](#task-2-lookalike-model)
- [Task 3: Customer Segmentation / Clustering](#task-3-customer-segmentation--clustering)
- [Evaluation Criteria](#evaluation-criteria)
- [Repository Structure](#repository-structure)
- [Instructions for Running the Code](#instructions-for-running-the-code)
- [License](#license)

## Overview
The provided eCommerce dataset includes three files:
1. **Customers.csv** - Customer profile information.
2. **Products.csv** - Product details, including prices.
3. **Transactions.csv** - Information about the transactions made by customers.

The goal of the assignment is to perform data analysis, build predictive models, and derive actionable insights that could help the company improve its business strategy.

## Task 1: Exploratory Data Analysis and Business Insights
- Perform exploratory data analysis (EDA) on the provided datasets.
- Derive at least 5 business insights based on the data analysis.

### Deliverables:
- **EDA Code**: A Jupyter Notebook or Python script with the code for EDA.
- **Business Insights**: A PDF report summarizing 5 business insights.

## Task 2: Lookalike Model
- Build a Lookalike Model that takes customer information as input and recommends 3 similar customers based on their profile and transaction history.
- The model will calculate similarity scores for each customer and provide the top 3 lookalikes for each customer.

### Deliverables:
- **Lookalike.csv**: A CSV file mapping customer IDs to their top 3 lookalikes and similarity scores.
- **Lookalike Model Code**: A Jupyter Notebook or Python script explaining the model development.

## Task 3: Customer Segmentation / Clustering
- Perform customer segmentation using clustering techniques based on both customer profile and transaction data.
- Calculate clustering metrics, including the DB Index, and visualize the clusters.

### Deliverables:
- **Clustering Report**: A PDF report detailing the number of clusters formed, DB Index, and other relevant metrics.
- **Clustering Code**: A Jupyter Notebook or Python script containing the clustering code.

## Evaluation Criteria
The evaluation of this assignment will be based on the following criteria:
- **Exploratory Data Analysis (25%)**: Depth of analysis and quality of insights.
- **Business Insights (15%)**: Relevance and actionability of insights derived from the EDA.
- **Lookalike Model (30%)**: Model accuracy, logic, and quality of recommendations.
- **Customer Segmentation (30%)**: Clustering logic, metrics, and visual representation of clusters.

## Repository Structure
The repository contains the following files:
- `FirstName_LastName_EDA.pdf`: PDF report for Task 1 (EDA and Business Insights).
- `FirstName_LastName_EDA.ipynb`: Jupyter Notebook for Task 1 (EDA and Business Insights).
- `FirstName_LastName_Lookalike.csv`: CSV file for Task 2 (Lookalike Model).
- `FirstName_LastName_Lookalike.ipynb`: Jupyter Notebook for Task 2 (Lookalike Model).
- `FirstName_LastName_Clustering.pdf`: PDF report for Task 3 (Customer Segmentation).
- `FirstName_LastName_Clustering.ipynb`: Jupyter Notebook for Task 3 (Customer Segmentation).

## Instructions for Running the Code

1. Open the **Google Colab** link provided for each notebook.
   - Click on the Jupyter notebook link for the task you want to work on, or open directly in Google Colab.
   
2. **Upload the required datasets**:
   - You can upload the `Customers.csv`, `Products.csv`, and `Transactions.csv` files to your Colab environment using the following code in the notebook:
     ```python
     from google.colab import files
     uploaded = files.upload()
     ```
   - After running this code, select the datasets from your local machine to upload.

3. **Install required dependencies** (if needed):
   - If there are any missing dependencies, install them using:
     ```python
     !pip install pandas matplotlib seaborn scikit-learn
     ```

4. **Run the code cells** in the provided notebooks to perform the tasks. The results will be shown within the Colab environment.

5. For **Task 2 (Lookalike Model)**, the `Lookalike.csv` will be generated as output.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
