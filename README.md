# Vortex Tech AI/ML Internship - Week 3: Regression and Clustering

## Project Summary
This repository contains solutions for Week 3 of the Vortex Tech AI/ML Internship track. It covers continuous target prediction (Regression) and unsupervised pattern discovery (Clustering) using `scikit-learn`.

## Implementation Details
1. Regression Model:
   - Predicts house prices based on area, bedrooms, and property age.
   - Evaluated using **Root Mean Squared Error (RMSE)** and **R² Score**.
   - Evaluates both **Linear Regression** and **Random Forest Regressor**.
2. K-Means Clustering:
   - Features scaled using `StandardScaler`.
   - Used the **Elbow Method** (plotting cluster count vs. inertia) to choose $K=3$.
   - Clusters visualized using a 2D scatter plot (Square Feet vs Price).

## How to Run
1. Clone this repository:
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/vortextech-aiml-week3.git
