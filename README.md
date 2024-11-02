# Video Game Sales Analysis

## Description

This project focuses on analyzing video game sales data using the **Pandas** library in Python. The goal is to extract insights and trends from the dataset, which includes information on various video games, such as sales figures across different platforms and genres.

## Installation

To use Pandas, install the library with pip:

```bash
pip install pandas
```

## Key Features

- **DataFrame Creation**: Create and manipulate DataFrames to represent video game sales data.
- **Data Selection**: Utilize `.loc` and `.iloc` methods for selecting and filtering data.
- **Handling Missing Values**: Techniques for detecting and managing missing data entries.
- **Data Analysis**: Functions for aggregating sales data and generating insights based on various criteria.

## Practice

In this project, I practice using Pandas to perform tasks such as:

- Importing and cleaning video game sales data.
- Analyzing sales by platform and genre.
- Generating statistics and visualizations to present findings.

## Example

Here’s a simple example of creating a DataFrame with sample video game sales data:

```python
import pandas as pd

data = {
    'Name': ['Game A', 'Game B', 'Game C'],
    'Platform': ['PS4', 'X360', 'PC'],
    'Year': [2020, 2019, 2021],
    'Global_Sales': [5.5, 3.8, 8.2]
}

df = pd.DataFrame(data)
print(df)
```

## Conclusion

Pandas is a powerful tool for data analysis in Python. This project enhances my understanding of data manipulation and prepares me for more advanced data analysis tasks in the future.
