# CO₂ Emissions and Ad Click Prediction

This project explores two key data science tasks:
1. **Estimating missing CO₂ emissions** for various car models using linear regression.
2. **Predicting user ad click behavior** based on anonymized user features.

It is designed as a foundational assignment introducing Python's data science stack including `pandas`, `numpy`, and `matplotlib`.

---

## 📁 Project Structure

- **CA0.ipynb** – Jupyter notebook containing all code and analysis.
- **data/** – Folder containing input datasets (not included here for size/privacy).
- **README.md** – This file.

---

## 🚗 Part 1: CO₂ Emissions Estimation

We work with an automotive dataset containing:
- Make, model, vehicle class
- Engine specs, fuel consumption metrics
- Some missing **CO₂ emission values**

### Approach:
- Visualize and explore data
- Identify the most influential features (e.g., fuel consumption)
- Use **simple linear regression** to impute missing CO₂ values

---

## 📊 Part 2: Ad Click Prediction

We analyze data from **1,000 users** exposed to an online ad. The dataset includes:
- Demographic and behavioral features
- A binary target: `Clicked on Ad`

### Approach:
- Handle missing values with mean imputation
- Normalize features
- Identify the most predictive indicator
- Predict clicks using thresholding techniques

---

## 🔧 Technologies Used

- **Python 3.x**
- **pandas** – data manipulation
- **numpy** – numerical operations and broadcasting
- **matplotlib** – visualizations

---

## ✅ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/SarinaHamedani/missing-data-regression
   cd missing-data-regression
2. Launch the notebook
    ```bash
    jupyter notebook CA0.ipynb