# Data Analysis Project (Google Colab)

This project is a data analysis notebook created using Python in Google Colab.  
The project loads and analyzes a dataset to explore different variables and understand patterns in the data.

---

## Project Overview

The goal of this project is to practice data analysis using Python.  
The dataset is loaded from an online source and explored using the pandas library.

The notebook performs basic operations such as:

- Loading a dataset from a URL
- Viewing dataset structure
- Exploring columns and records
- Performing basic analysis

---

## Technologies Used

- Python
- Google Colab
- Pandas

---

## Dataset

The dataset is loaded directly from GitHub using a CSV file.

Example code used:

```python
import pandas as pd

df = pd.read_csv("DATASET_URL")
df
