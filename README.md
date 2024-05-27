# BankChurnTensorFlow

---

# Customer Churn Prediction using Deep Learning

This repository contains a project on customer churn prediction using deep learning techniques implemented with TensorFlow. The aim of this project is to predict customer churn based on various features and provide insights into customer retention strategies.

## Project Overview

Customer churn prediction is crucial for businesses to understand the reasons behind customer attrition and to develop strategies to retain valuable customers. In this project, we use a dataset containing customer information and build a deep learning model to predict the likelihood of customers churning.

## Dataset

The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/datasets) and includes various features such as:

- Customer ID
- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary
- Exited

## Project Structure

The project is organized into the following sections:

1. **Data Preprocessing**: This section involves cleaning and preparing the data for analysis. It includes handling missing values, encoding categorical variables, and scaling numerical features.

2. **Exploratory Data Analysis (EDA)**: In this section, we perform an in-depth analysis of the dataset to understand the distribution of features and their relationship with the target variable (Exited).

3. **Model Building**: We build and train a deep learning model using TensorFlow. The model architecture, hyperparameters, and training process are detailed in this section.

4. **Model Evaluation**: This section covers the evaluation of the model's performance using roc_auc_score

5. **Conclusion**: We summarize the findings of the project and provide recommendations for future work.

## Requirements

To run the code in this repository, you need to have the following packages installed:

- Python 3.7+
- TensorFlow 2.x
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

You can install the required packages using the following command:

```bash
pip install tensorflow pandas numpy matplotlib scikit-learn
```

## Usage

1. Clone the repository:
   
   ```bash
   git clone https://github.com/JoaoPedroOlavo/BankChurnTensorFlow
   ```

2. Navigate to the project directory:
   
   ```bash
   cd BankChurnTensorFlow
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook Bank_Churn_TensorFlow.ipynb
   ```

4. Run the cells in the notebook to preprocess the data, build the model, and evaluate its performance.

## References

This project references the following resources:

- [TensorFlow Documentation](https://www.tensorflow.org/learn)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please open an issue or submit a pull request.


## Contact

If you have any questions or feedback, feel free to contact me at joaopedroolavo13@gmail.com.

---
