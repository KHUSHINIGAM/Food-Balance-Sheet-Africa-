# 🌍 Food Balance Sheets Analysis 📊

Welcome to the Food Balance Sheets Analysis project! 🍽️

## Overview ℹ️

This project analyzes food balance sheets data from Africa to gain insights into food production, consumption, and  other useful information.
It aims to provide a quick intro into 'pandas' which is a pyhton library built on Numpy which is used for data manipulation, with other ways of indexing other than integers. 📈
I have used Google Colab for this project. 💻

## Features ✨

- **Data Exploration**: Explore food balance sheets data from Africa.
- **Retrieving information** : Code has been written to retrieve usefyl information from the dataset.

  ## Incorrect Output in Code

### Description:
The current implementation of the groupby() function is producing incorrect output. The expected output is the year with highest sum of stock variation, but the actual output is Domestic supply quantity .

### Code Snippet:
```python
selected_columns = df[['Element', 'Y2014', 'Y2015', 'Y2016', 'Y2017', 'Y2018']]
grouped_data = selected_columns.groupby('Element').sum()
year_highest_sum_stock_variation = grouped_data.sum(axis=1).idxmax()
print(year_highest_sum_stock_variation)
```
## Conclusion ❕
Thank you for exploring my project! I hope you find it useful and informative. If you have any questions or feedback, feel free to reach out to me.



