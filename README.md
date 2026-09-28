# Cross-section-prediction-regression
#
clean_data.csv - input data
1_split_data.py - split into train / validation / test (60/20/20)
2_train_model.py - train model, evaluate on train + validation
3_test_model.py - final test with all metrics and charts
results/ - metrics tables, predictions and charts
# run
pip install pandas numpy scikit-learn matplotlib joblib
python 1_split_data.py
python 2_train_model.py
python 3_test_model.py

#Results (test set)

R2 (log10) = 0.9998, about 90% of predictions within 10% of the true value.
