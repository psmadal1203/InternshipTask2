# InternshipTask2
Task 2 : Calculate summary statistics Calculate summary statistics (mean, median, mode, standard deviation) for a dataset
Steps Taken:
1. Imported Necessary Libraries:
    import pandas as pd
    import numpy as np
    from scipy import stats
2. Loaded the Datasets:
# Load the Titanic test and train datasets
  train_data = pd.read_csv('train.csv')
  test_data = pd.read_csv('test.csv')
3. Calculated Summary Statistics:
  # Calculate mean, median, mode, and standard deviation
  mean_values = train_data.mean()
  median_values = train_data.median()
  mode_values = train_data.mode().iloc[0]  # Mode for each column
  std_dev_values = train_data.std()
4. Summary Statistics:
Mean:
print("Mean Values:\n", mean_values)
Median:
print("Median Values:\n", median_values)
Mode:
print("Mode Values:\n", mode_values)
Standard Deviation:
print("Standard Deviation Values:\n", std_dev_values)

 
