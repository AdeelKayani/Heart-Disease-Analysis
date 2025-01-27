# Heart-Disease-Analysis

This project analyzes the **Heart Disease UCI Dataset** to explore patterns, trends, and key health metrics related to heart disease. It uses Python libraries like `pandas`, `matplotlib`, and `seaborn` for data analysis and visualization.

---

## Key Features

1. **Basic Analysis**:
   - Checks dataset size, missing values, and column summaries.
   - Identifies how many patients have heart disease and how many don’t.

2. **Statistical Insights**:
   - Calculates average and median values for:
     - Resting blood pressure (`trestbps`)
     - Serum cholesterol (`chol`)
     - Maximum heart rate (`thalach`)
   - Identifies outliers in key metrics using the IQR method.

3. **Visualization**:
   - Distribution plots for age, heart disease severity, and chest pain types.
   - Box plots for cholesterol and blood pressure levels.
   - Custom color palettes for clear and visually appealing charts.

4. **Key Comparisons**:
   - Compares cholesterol levels between patients with and without heart disease.
   - Highlights exercise-induced angina distribution.

---

## How to Run

1. Ensure Python 3.x is installed.
2. Install required libraries:
   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Place the `heart_disease_uci.csv` file in the same folder as the script.
4. Run the script using a Python IDE or Jupyter Notebook.

---

## Output

- **Console**: Key statistics, outlier detection, and comparisons.
- **Visuals**: Count plots, histograms, and box plots for key metrics.

---

## Dataset Information

The dataset contains:
- **`age`**: Patient age.
- **`sex`**: Gender (0 = Female, 1 = Male).
- **`cp`**: Chest pain type.
- **`trestbps`**: Resting blood pressure.
- **`chol`**: Serum cholesterol level.
- **`num`**: Heart disease severity (0 = No disease, 1-4 = Increasing severity).

