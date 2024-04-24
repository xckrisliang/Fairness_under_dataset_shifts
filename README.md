This repositry stores the prediction result files for each trained models (LSTM neural network models and logistic regression models) on each test set to simulate different level of dataset shifts.

Logistic regression results
- for logistic_young model stored at /in_hospital_mortality_0_logistic/test num/predictions/all.all.l2.C0.001.csv
- for logistic_mix model stored at /in_hospital_mortality_50_logistic/test num/predictions/all.all.l2.C0.001.csv
- for logistic_old model stored at /in_hospital_mortality_100_logistic/test num/predictions/all.all.l2.C0.001.csv

LSTM neural network models results: stored at
- Fairness_under_dataset_shifts/predictions_neural_net/CSVs/


All the csv files are in the format:

| stay | prediction | y_true |

representing the predicted mortality risk and the true mortality condition of the patients' stay. 
