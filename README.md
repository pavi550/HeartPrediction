# Heart Disease Prediction - EDA Project

## Team 11 Members
- Janani Srinivasan
- Monisha B R
- Praveenkumar
- Varsha
- Viswanath Viralam Ramamurthy

## Project Overview
This project involves exploratory data analysis (EDA) on a heart disease prediction dataset. The dataset integrates both traditional clinical indicators and an additional QuantumPatternFeature that captures complex, non-linear relationships to enhance predictive modeling.

---

## Dataset Details
- **Source**: [Kaggle - Heart Prediction Dataset (Quantum)](https://www.kaggle.com/datasets/shantanugarg274/heart-prediction-dataset-quantum)
- **Samples**: 500 entries
- **Features**:
  - Age
  - Gender
  - Blood Pressure
  - Cholesterol
  - Heart Rate
  - QuantumPatternFeature
- **Modifications**:
  - Removed duplicate records
  - Filled missing values with appropriate strategies

---

## Technologies Used
- **Python**
- **Libraries**:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`

---

## Project Structure
```
|-- Dataset.csv
|-- EDA_Project_Team11.ipynb
|-- README.md
```

---

## Key Steps Performed

### ✨ Data Loading
- Loaded the dataset using `pandas`.
- Performed initial inspections with `.head()`, `.info()`, and `.describe()`.

### ✨ Data Cleaning
- Removed duplicates.
- Handled missing values using domain-appropriate imputations.

### ✨ Exploratory Data Analysis (EDA)
- Correlation heatmap to understand feature relationships.
- Histograms and pairplots to visualize data distributions and feature interactions.
- Individual feature analysis.

### ✨ Key Insights
- Age and Cholesterol show strong correlation with heart disease.
- QuantumPatternFeature significantly enhances the predictive power.
- Gender had minor variations in heart disease prediction.

---

## Future Work
- Apply classical machine learning models.
- Explore quantum machine learning techniques.
- Model interpretation and feature importance analysis.

---

## How to Run the Project
1. Clone the repository.
2. Ensure all required libraries are installed.
3. Open the `EDA_Project_Team11.ipynb` notebook.
4. Run the cells to reproduce the EDA.

```bash
pip install pandas numpy matplotlib seaborn
```

---

## License
This project is licensed for educational and research purposes.

---

## Acknowledgements
- Dataset modified from Kaggle: [Heart Prediction Dataset (Quantum)](https://www.kaggle.com/datasets/shantanugarg274/heart-prediction-dataset-quantum)

---

**Thank you for visiting our project!**

