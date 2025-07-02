# Medical Personal Cost Data Analysis & Smoker Status Prediction

## Project Overview
This analytical project leverages **medical personal cost data** to identify patterns and predict an individual's smoker status. By applying a **Naive Bayes classification model** and comprehensive data visualizations, the project aims to extract actionable insights and understand the factors influencing smoking habits and associated costs, supporting data-driven understanding.

## Dataset
The dataset used is **Medical Personal Cost** (in .csv format), which contains information related to individual medical expenses, including demographic variables and smoking habits.

## Methodology
This project follows standard data analysis phases:
1.  **Data Exploration:** Displaying general information about the dataset, checking for missing values and outliers, performing descriptive statistical analysis, and creating initial visualizations to understand data patterns.
2.  **Data Preparation:** Handling missing values, adding new features, performing encoding on categorical variables, normalizing or standardizing numerical features (if necessary), and removing duplicate data to ensure a clean and ready-to-process dataset.
3.  **Predictive Modeling:** Creating a target column (`smoker`), separating features and target, splitting data into training and testing sets, then implementing a **Gaussian Naive Bayes Classification** model using the training data to predict smoker status.
4.  **Prediction and Model Evaluation:** Making predictions on the test data and evaluating the model's accuracy to assess its performance.
5.  **Results Visualization & Insight Extraction:** Presenting key visualizations such as smoker classification by age and count, a *Confusion Matrix* to assess model performance, the relationship between smoking habits and medical costs, analysis of medical costs by gender and smoking habits, and the interaction between BMI, smoking habits, and medical costs. This step aims to derive clear insights from the data.

## Technologies and Tools
* **Programming Language:** Python
* **Python Libraries:**
    * `pandas` and `numpy` for data manipulation and analysis.
    * `scikit-learn` for implementing classification models and evaluation.
    * `matplotlib` and `seaborn` for comprehensive data visualization.
* **Environment:** Google Colab (Jupyter Notebook)

## Key Results & Insights
* The Naive Bayes Classification model successfully predicted smoker status with an **accuracy of 92%**.
* Visualizations provide clear insights into smoker characteristics and how smoking habits correlate with individual medical costs, enabling a deeper understanding of the dataset.

## How to Run the Notebook
1.  Ensure you have Python and the aforementioned libraries installed in your environment.
2.  Download the `Medical_Personal_Cost_Datasets_Analysis.ipynb` and `medical_personal_cost.csv` files to your local directory.
3.  Open the notebook using Jupyter Notebook or upload it to Google Colab.
4.  Run each cell sequentially to reproduce the analysis and visualizations.

## Contact
[[Fathimah Ella Syarif](https://www.linkedin.com/in/fathimahellasyarif/)]
