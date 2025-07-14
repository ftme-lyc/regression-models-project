# Affordable Property Rental Price Prediction

This project focuses on predicting rental prices for affordable properties in Australia using machine learning regression models. It aims to provide accurate rental price estimates to support landlords, investors, and tenants in making informed decisions.

## Key Features
- Uses a dataset with 19 property-related features and rental prices.
- Models explored:  
  - Multivariate Linear Regression  
  - ElasticNet Regression  
  - K-Nearest Neighbors (KNN) Regression
- Evaluation based on RMSE and MAE metrics.
- Data preparation includes cleaning, feature engineering, and transformation.
- Addresses challenges like outliers, high dimensionality, and hyperparameter tuning.

## Results Summary
- All models outperform the baseline (Dummy Regressor).
- KNN model achieved the best validation RMSE of 10.57.
- Models improve pricing accuracy, benefiting stakeholders in the affordable housing market.
- Ethical considerations around data privacy and fairness were addressed.

## Usage
1. Prepare the dataset.
2. Run model training scripts to train and tune regression models.
3. Evaluate model performance using validation and test data.
4. Use the best-performing model for rental price predictions.

## Future Work
- Incorporate more diverse data sources and economic indicators.
- Experiment with advanced models like Random Forest and XGBoost.
- Enhance fairness by including data from underrepresented communities.

## License
This project is for educational and research purposes.

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/ftme-lyc/regression-models-project.git
   cd regression-models-project
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Upload the dataset:

   Place rental_training.csv, rental_validation.csv, and rental_testing.csv in the same directory as the notebooks, or upload them to your Drive if using Colab.
5. Run the notebooks:

   Open the following files in Jupyter Notebook or VS Code:
   - 36106_at1_25589351_experiment_0.py
   - 36106_at1_25589351_experiment_1.py
   - 36106_at1_25589351_experiment_2.py
   - 36106_at1_25589351_experiment_3.py


