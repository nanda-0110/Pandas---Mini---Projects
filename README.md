# Pandas---Mini---Projects
# Movie Analytics Using Pandas

## Project Overview

This project performs exploratory data analysis (EDA) on a movie dataset using Python and Pandas.

The goal of the project is to practice and apply core Pandas concepts such as:

- Reading CSV files
- DataFrame exploration
- Filtering data
- Indexing and selection
- Creating new columns
- Aggregations
- Statistical analysis
- Finding maximum and minimum values
- Movie profitability analysis

---

## Technologies Used

- Python
- Pandas
- Jupyter Notebook

---

## Dataset Information

The dataset contains information about movies, including:

- Title
- Industry
- Release Year
- IMDb Rating
- Studio
- Budget
- Revenue
- Language

---

## Analysis Performed

### Dataset Exploration

- Total Movies
- Total Studios
- Total Languages
- Data Types
- Column Information

### Movie Analysis

- Highest IMDb Rated Movie
- Lowest IMDb Rated Movie
- Highest Revenue Movie
- Lowest Revenue Movie
- Highest Budget Movie
- Lowest Budget Movie

### Feature Engineering

Created new columns:

#### Age

```python
Age = Current Year - Release Year
```

#### Profit

```python
Profit = Revenue - Budget
```

#### Profit Percentage

```python
Profit Percentage = ((Revenue - Budget) / Budget) * 100
```

### Studio Analysis

- Marvel Studios Movies
- Best Marvel Movie
- Most Profitable Marvel Movie
- Average Marvel IMDb Rating
- Average Marvel Revenue

### Language Analysis

- English Movies
- Hindi Movies
- Telugu Movies
- Average IMDb Rating by Language
- Average Revenue by Language

### Profit Analysis

- Most Profitable Movie
- Least Profitable Movie
- Highest Profit Percentage Movie
- Lowest Profit Percentage Movie

---

## Key Pandas Concepts Practiced

- `read_csv()`
- `head()`
- `tail()`
- `shape`
- `columns`
- `unique()`
- `loc[]`
- `set_index()`
- `reset_index()`
- `apply()`
- `lambda`
- `idxmax()`
- `idxmin()`
- Boolean Filtering
- Aggregations (`mean`, `sum`, `max`, `min`)

---

## Learning Outcomes

Through this project I learned:

- How to work with real-world datasets
- How to filter and analyze data efficiently
- How to create meaningful insights from raw data
- How to use Pandas for exploratory data analysis
- How to structure a complete data analysis project
## Acknowledgement

This project was built as part of my learning journey in Pandas.

I learned the concepts and completed the analysis by following the Pandas course from Codebasics and applying the concepts independently on this project.
