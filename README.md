# ECGR_5105_001_Assignment_1
This repository is the solutions of assignment 1 of ECGR 5105

# Linear Regression with Gradient Descent

This repository contains an implementation of **Linear Regression using Gradient Descent** for analyzing the relationship between a single explanatory variable and an output variable. The model is trained independently for each feature (`x1`, `x2`, and `x3`) to evaluate their individual impact on `y`.

## Project Structure
- `ECGR_5105_Assignment_1_Liyuan.ipynb` – Jupyter Notebook containing the full implementation and analysis.
- `README.md` – Project documentation (this file).
- `report.tex` – LaTeX report file for generating a detailed report in PDF format.

## Implementation Details
- **Dataset:** CSV file with three explanatory variables (`x1`, `x2`, `x3`) and one target variable (`y`).
- **Algorithm:** Gradient Descent for optimizing the linear regression model.
- **Training:** Each feature is trained in isolation, resulting in three separate models.
- **Evaluation:** Loss is analyzed across different learning rates, and the best feature for predicting `y` is identified.

## Results
1. **Final Models for Each Variable:**
   - `y = θ0 + θ1 * x1`
   - `y = θ0 + θ1 * x2`
   - `y = θ0 + θ1 * x3`
   
   The trained parameters for each model are reported in the Jupyter Notebook.

2. **Effect of Learning Rate:**
   - **Higher learning rate (> 0.1):** Leads to faster convergence but may cause instability.
   - **Lower learning rate (< 0.01):** Leads to slow convergence and may require more iterations.
   - **Excessive learning rate:** Causes gradient explosion and divergence.

3. **Best Explanatory Variable:**
   - The feature with the lowest loss is identified as the best predictor for `y`.

## Usage Instructions
1. Install dependencies:
   ```sh
   pip install numpy pandas matplotlib
   ```
2. Run the Jupyter Notebook:
   ```sh
   jupyter notebook ECGR_5105_Assignment_1_Liyuan.ipynb
   ```
3. Modify parameters (e.g., learning rate) to observe their impact.

## Author
- **Liyuan**
- Course: ECGR 5105 – Machine Learning
