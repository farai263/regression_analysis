# Regression Analysis

This project is a beginner-friendly multiple linear regression analysis built around a dummy advertising dataset. It explores how different marketing variables relate to sales and uses regression to estimate how those factors influence outcomes.

## What the project does

The project looks at a dataset with information such as:

- TV spending
- Radio spending
- Social Media spending
- Influencer category
- Sales

It then:

- reviews and cleans the data
- checks for missing values and data quality issues
- visualizes relationships between advertising spend and sales
- converts categorical information (like influencer type) into a format suitable for modeling
- builds a multiple linear regression model
- evaluates the model to see how well it explains sales patterns

In plain terms, this project helps answer questions like:

- Which marketing channels appear to matter most for sales?
- How do different types of influencers relate to performance?
- Can we predict future sales based on marketing spend?

## Who the project is for

This project is intended for:

- students learning data analysis or statistics
- beginners exploring Python and machine learning
- people interested in marketing analytics
- anyone who wants a simple, clear example of regression in practice

You do not need to be an expert to follow along. A basic understanding of spreadsheets and Python is helpful, but the notebook is written to be approachable and easy to follow.

## Project files

- `data_555_regression_analysis_project.ipynb` — the main notebook containing the analysis
- `dummy_data_hss.csv` — the dataset used in the project
- `project_proposal.rtf` — project proposal document
- `summative_report.rtf` — report summarizing the work

## How to use it

### Option 1: Run the notebook locally

1. Clone or download this repository.
2. Open a terminal in the project folder.
3. Make sure you have Python installed.
4. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

5. Start Jupyter Notebook or JupyterLab:

```bash
jupyter notebook
```

6. Open `data_555_regression_analysis_project.ipynb`.
7. Run the notebook cells from top to bottom.

### Option 2: Run in Google Colab

1. Open Google Colab.
2. Upload the notebook file from this repository.
3. Upload `dummy_data_hss.csv` to your Colab environment if needed.
4. Run the notebook cells in order.

### What to expect

When you run the analysis, you should be able to:

- view the dataset and understand its structure
- inspect trends and patterns in the data
- see visualizations of advertising spend versus sales
- follow the model-building process
- review the final regression results and interpretation

## Requirements

This project uses Python libraries commonly used for data science, including:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Summary

This repository is a practical example of how multiple linear regression can be used to analyze business data. It is a useful learning tool for understanding how advertising-related variables can be modeled and interpreted in a real-world context.
