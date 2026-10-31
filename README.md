# ☕ Understanding Sales Trends in Indonesia's Coffee Market

**Machine Learning-Based Analysis of Coffee Retail Sales and Customer Brand Loyalty**

## About the Project

This project analyses retail coffee sales data from Indonesia to understand customer purchasing patterns and brand loyalty. It uses machine learning classification algorithms to classify customers into different loyalty categories and compare model performance.

## Dataset

- **Dataset:** Coffee.csv
- **Records:** 499
- **Features:** 26
- **Target Variable:** Customer Brand Loyalty Tier
- **Problem Type:** Multiclass Classification
- 
## Technologies Used

- Python
- Google Colab
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn

## Machine Learning Algorithms

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Support Vector Machine (SVM)
4. Decision Tree Classifier

## Model Performance

| Algorithm           | Accuracy |  F1-Score |
| ------------------- | -------: | --------: |
| Logistic Regression |      92% |     0.920 |
| KNN                 |      67% |     0.667 |
| SVM                 |      81% |     0.796 |
| **Decision Tree**   |  **98%** | **0.980** |

**Best-performing model:** Decision Tree Classifier with a reported accuracy of 98%.

## Conclusion

The Decision Tree Classifier achieved the highest reported accuracy among the four algorithms. This project demonstrates how machine learning can be applied to retail sales data to analyse customer behaviour and classify brand loyalty.

## Repository Contents

- `Coffee.csv` – Dataset
- `Coffee_Sales_Analysis.ipynb` – Jupyter/Colab notebook
- `README.md` – Project documentation
