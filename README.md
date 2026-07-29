# World's Oldest Businesses Analysis

A data analysis project exploring the world's oldest continuously operating businesses using Python and pandas.

## Project Overview

This project analyzes historical business data to answer questions such as:

- Which is the oldest business on each continent?
- Which countries lack data on their oldest businesses?
- Which business categories have survived the longest?
- How do business longevity and categories vary across continents?

The project focuses on merging datasets, and performing descriptive analysis using pandas.

---

## Dataset

The project uses four datasets:

- `businesses.csv` – Existing oldest businesses by country.
- `new_businesses.csv` – Additional businesses not included in the original dataset.
- `countries.csv` – Country and continent information.
- `categories.csv` – Business category lookup table.

---

## Technologies Used

- Python 3
- pandas
- Jupyter Notebook
- VS Code

---

## Project Structure

```
world's_oldest_businesses/
│
├── data/
│   ├── businesses.csv
│   ├── new_businesses.csv
│   ├── countries.csv
│   └── categories.csv
│
├── oldest_business.ipynb
```

---

## Analysis Performed

### Data Preparation

- Loaded CSV datasets
- Combined business datasets
- Merged country and category information
- Identified missing business records

### Business Questions

- Oldest business on each continent
- Countries missing oldest business data
- Oldest business category by continent
- Comparison of business longevity across continents

---

## Skills Demonstrated

- Data cleaning
- Data wrangling
- Data merging (`merge`, `concat`)
- Grouping and aggregation
- Handling missing values
- Exploratory data analysis (EDA)
- Descriptive data analysis

---

## Sample Libraries

```python
import pandas as pd
```

---

## Key Pandas Methods Used

- `read_csv()`
- `merge()`
- `concat()`
- `groupby()`
- `sort_values()`
- `query()`
- `drop()`
- `isnull()`
- `reset_index()`

---

## Future Improvements

- Add visualizations using Matplotlib and Seaborn
- Perform a more comprehensive Exploratory Data Analysis (EDA)
- Build an interactive dashboard using Power BI or Tableau
- Include additional historical business datasets

---

## Author

**Sabrina Farah**

Aspiring Data Analyst / Data Scientist building projects with Python, SQL, and data visualization.
