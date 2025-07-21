
# Decision Tree Regression on Autos Dataset

This project demonstrates how to apply **Decision Tree Regression** to an **Automobile Dataset** to predict car prices based on various features. The notebook provides a complete workflow starting from data preprocessing to model evaluation.

## Project Overview

### Objective:
To predict automobile prices using decision tree regression, helping stakeholders understand how different car features influence pricing.

### Dataset:
- **Autos Dataset**  
- Common columns include:
  - `make` (manufacturer)
  - `fuel-type`
  - `num-of-doors`
  - `engine-size`
  - `horsepower`
  - `curb-weight`
  - `price` (target variable)

### Key Steps:
1. **Data Loading & Exploration**
2. **Handling Missing Values**
3. **Feature Selection & Engineering**
4. **Model Building using DecisionTreeRegressor**
5. **Hyperparameter Tuning (optional)**
6. **Model Evaluation using R² score and RMSE**

---

## Installation & Requirements

### Libraries Used:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### Recommended Environment:
- Python 3.7+
- Jupyter Notebook / Google Colab / VSCode

---

## Usage

1. Clone this repository:

```bash
git clone <your-repo-link>
```

2. Open the notebook:

```bash
cd <repo-folder>
jupyter notebook "Decision Tree_Regression_Autos Data Set (1).ipynb"
```

3. Run the notebook step by step to train and evaluate the model.

---

## Results

- The model captures the non-linear relationships in automobile pricing.
- Decision Trees help visualize feature importance in pricing decisions.

---

## File Structure

```
📦 Decision Tree Regression - Autos Dataset
 ┣ 📄 Decision Tree_Regression_Autos Data Set (1).ipynb
 ┗ 📄 README.md
```

---

## Author

- **Pranav Gupta**

---

## License

This project is open-source and available under the [MIT License](LICENSE).
