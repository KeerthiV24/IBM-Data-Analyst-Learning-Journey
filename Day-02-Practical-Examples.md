
# Example 1: Reading a CSV file using Python

import pandas as pd

data = pd.read_csv("sales.csv")

print(data.head())

# Example 2: Understanding the dataset

print(data.shape)
print(data.columns)
print(data.info())
