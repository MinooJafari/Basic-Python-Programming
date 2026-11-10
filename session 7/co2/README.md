# CO2 Data Analysis with Pandas and NumPy

## About the Project
This project focuses on exploring and analyzing a CO2 emissions dataset using Python. The dataset contains 500 records with information about engine size, number of cylinders, fuel consumption, and CO2 emissions.

The main goal is to practice basic data analysis, explore statistical summaries, and calculate the average CO2 emissions using different approaches.

## Technologies Used
- Python
- Pandas
- NumPy
- Jupyter Notebook

## Dataset Description

The dataset (`co2.csv`) contains 500 rows and 4 columns:

| Column | Description |
|---|---|
| engine | Engine size |
| cylandr | Number of cylinders |
| fuelcomb | Combined fuel consumption |
| out1 | CO2 emissions |

## Project Tasks

- Load the CSV dataset using Pandas.
- Explore the first and last 20 rows.
- Generate statistical summaries using `describe()`.
- Access individual rows using `loc[]`.
- Generate random numbers using NumPy.
- Calculate the average of random numbers using `np.mean()`.
- Calculate the average CO2 emissions using a Python for loop.

## Example Code

### Loading and Exploring Data

```python
import pandas as pd

df = pd.read_csv('co2.csv')

df.describe()
df.head(20)
df.tail(20)
```

### Calculating the Average with NumPy

```python
import numpy as np

numbers = np.random.randint(1, 500, 500)
average = np.mean(numbers)

print("Average:", average)
```

### Calculating Average CO2 Emissions with a Loop

```python
miyangin = 0

for i in range(0, 500):
    miyangin += df['out1'][i]

miyangin = miyangin / 500

print(miyangin)
```

## Results

- Total records: 500
- Average CO2 emissions: 268.026

## Learning Objectives

- Understanding CSV files and datasets.
- Practicing data exploration with Pandas.
- Learning basic statistical analysis.
- Working with NumPy arrays and mathematical functions.
- Understanding loops and manual calculations in Python.

