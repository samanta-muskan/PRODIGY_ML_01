# Machine Learning Internship Projects

This repository contains the machine learning tasks completed as part of my internship at Prodigy Infotech. Each project demonstrates the application of machine learning algorithms to real-world problems using Python and Google Colab.

## Projects

### Task 1: House Price Prediction using Linear Regression

**Objective:** Predict house prices based on property features.

- **Algorithm:** Linear Regression
- **Dataset:** [Kaggle – House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)
- **Features:**
  - Living Area (square feet)
  - Number of Bedrooms
  - Total Bathrooms
- **Evaluation Metrics:** MAE, MSE, RMSE, and R² Score
- **Notebook:** `House_Price_Prediction.ipynb`

### Task 2: Customer Segmentation using K-Means Clustering

**Objective:** Group mall customers into segments based on their annual income and spending behavior.

- **Algorithm:** K-Means Clustering
- **Dataset:** [Kaggle – Customer Segmentation Tutorial](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **Features:**
  - Annual Income (k$)
  - Spending Score (1–100)
- **Techniques:** Feature scaling, Elbow Method, and Silhouette Score
- **Notebook:** `Customer_Segmentation_KMeans.ipynb`

### Task 3: Cats vs Dogs Image Classification using SVM

**Objective:** Classify images into two categories: cats and dogs.

- **Algorithm:** Support Vector Machine (SVM) using `LinearSVC`
- **Dataset:** [Kaggle – Dogs vs. Cats](https://www.kaggle.com/competitions/dogs-vs-cats/data)
- **Techniques:**
  - Image resizing and preprocessing
  - Pixel normalization and feature extraction
  - Training and testing data splitting
  - Model evaluation using accuracy, classification report, and confusion matrix
- **Notebook:** `Cats_Dogs_SVM.ipynb`

## Technologies Used

- Python
- NumPy and Pandas
- Matplotlib and Seaborn
- Scikit-learn
- Pillow (PIL)
- Joblib
- Google Colab
- Jupyter Notebook

## Repository Structure

```text
PRODIGY_ML_01/
├── README.md
├── House_Price_Prediction.ipynb
├── Customer_Segmentation_KMeans.ipynb
└── Cats_Dogs_SVM.ipynb
```

*Note: The notebook filenames above should match the actual filenames in the repository.*

## How to Run

1. Open the required notebook in Google Colab.
2. Download the corresponding dataset from the linked Kaggle page.
3. Upload the dataset when prompted by the notebook.
4. Run the cells sequentially.
5. Review the model predictions, evaluation metrics, and visualizations.

## Author

**Muskan Samanta**
