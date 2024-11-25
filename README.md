# One-Hot Encoding Task

This project solves a one-hot encoding task for a DataFrame in Python without using `pd.get_dummies`. 

## Problem Description
Given a DataFrame with a single column containing categories (`human`, `robot`), the task is to transform it into a one-hot encoded format. 

## Algorithm
The solution involves iterating through the data and creating two new columns, `human` and `robot`, based on the values in the original column. The values in these columns are binary indicators (1 or 0)
