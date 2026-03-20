# Decision Tree - AI Data Analysis Project

## Overview
This project explores and implements the **Decision Tree algorithm** for classification tasks using the Lenses dataset.  
The goal is to understand how decision trees work and how different parameters affect model performance.

---

## Objectives
- Understand the working principle of Decision Tree
- Apply the model using `scikit-learn`
- Analyze the impact of parameters like `max_depth`, `min_samples_split`
- Visualize and interpret the trained model

---

## Dataset
- **Name:** Lenses Dataset (UCI Machine Learning Repository)
- **Link:** https://archive.ics.uci.edu/ml/datasets/Lenses
- **Samples:** 24
- **Features:** 4
- **Classes:** 3

The dataset is used to predict the suitable type of lenses for patients based on age, spectacle prescription, astigmatism, and tear production rate.

| Feature | Description | Values |
|---------|-------------|--------|
| Age | Patient's age group | 1: young, 2: pre-presbyopic, 3: presbyopic |
| Spectacle Prescription | Type of refractive error | 1: myope, 2: hypermetrope |
| Astigmatism | Whether astigmatic | 1: no, 2: yes |
| Tear Production Rate | Tear production speed | 1: reduced, 2: normal |

| Output | Meaning |
|--------|---------|
| 1 | Hard contact lenses |
| 2 | Soft contact lenses |
| 3 | No lenses recommended |

---

## Technologies Used
- Python
- Jupyter Notebook
- Scikit-learn
- Pandas / Numpy

---

## Methodology
- Data preprocessing
- Training Decision Tree model (CART algorithm)
- Using **Gini Index** as the splitting criterion
- Evaluating model performance
- Visualizing the decision tree structure

**Gini Index formula:**
```
Gini(t) = 1 - sum(p_i^2)
```
Where `p_i` is the proportion of samples belonging to class `i` at node `t`.

---

## Results
- Successfully implemented Decision Tree model on the Lenses dataset
- Observed how `max_depth` affects overfitting
- Gained insights into feature importance and splitting criteria

---

## How to Run
1. Open `ai-data-analysis.ipynb`
2. Run all cells using Jupyter Notebook

---

## Key Learnings
- Decision Tree is simple but powerful for classification tasks
- Easy to interpret compared to other ML models
- Needs proper tuning (pruning, `max_depth`) to avoid overfitting
- CART algorithm underlies both `DecisionTreeClassifier` and `DecisionTreeRegressor` in sklearn

---

## Author
**Huynh Tran Nhat Phuc**  
GitHub: https://github.com/PhucBeossss123
