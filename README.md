# DATA1030-GroupProject: National Park Service (NPS) "Things To Do" Analysis & Modeling

## Project Overview
This project analyzes the U.S. National Park Service (NPS) "Things To Do" dataset. We collect park activity data using the official NPS API, conduct exploratory data analysis, and build machine learning models for predicting key activity characteristics.

---

## Dataset
The raw data directly pulled from the API is saved as `raw_todo.csv`, and the final cleaned dataset used for exploratory data analysis is saved as `eda_todo.csv`.

For detailed descriptions of all variables in our final dataset, please refer to the [Data Description](data/data_description.md).

---

## Python Version & Package Dependencies

- **Python**: `3.14.6`
- **numpy**: `2.4.6`
- **matplotlib**: `3.11.0`
- **seaborn**: `0.13.2`
- **pandas**: `3.0.3`
- **scikit-learn**: `1.9.0`
- **requests**: `2.34.2`
- **jupyter**
- **python-dotenv**

---

## Repository Structure

```text        
.
├── data/               # Raw and preprocessed data
├── figures/            # Generated plots
├── results/            # Saved predictions, models, etc
├── report/             # Midterm report and final presentation slides
├── src/                # Source codes and Jupyter Notebooks
├──.gitignore
├── LICENSE
├── README.md
└── data1030project.yml

