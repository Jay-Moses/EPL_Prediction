# EPL Match Outcome Prediction

## Project Overview
In this project, we aim to predict the outcome of football matches in the English Premier League (EPL) using machine learning techniques.

## Project Steps
1. **Data Collection**: Scrape EPL match data using `requests`, `BeautifulSoup`, and `pandas`.
2. **Data Cleaning**: Process and prepare data for machine learning with `pandas`.
3. **Prediction Modeling**: Use `scikit-learn` to predict match winners.
4. **Evaluation and Optimization**: Measure errors and improve the model's accuracy.

## Code
The code for this project is organized into two main files:
- **scraping.ipynb**: A Jupyter notebook that scrapes EPL match data.
- **predictions.ipynb**: A Jupyter notebook that builds and evaluates the prediction model.

## Local Setup

### Installation
To run this project locally, please ensure you have the following installed:

- **JupyterLab**
- **Python 3.8+**

### Required Python Packages
Install the following Python packages to run the notebooks:
```bash
pip install pandas requests beautifulsoup4 scikit-learn
