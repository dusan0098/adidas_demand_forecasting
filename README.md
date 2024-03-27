# Sales Forecasting Project

This project develops a sales forecasting model using the CatBoost Regressor. It predicts sales based on historical data and article attributes. The repository contains the datasets used, the Jupyter notebook with the analysis, the trained CatBoost model, the results of Bayesian Optimization, and other supporting files.

## Project Structure

- `analysis.ipynb`: The Jupyter notebook with the complete analysis and model training.
- `article_attributes.txt`: Attribute data of the sold articles.
- `sales.txt`: Historical sales data per article, week, and country.
- `best_catboost_model.cbm`: The trained CatBoost model ready for predictions.
- `bo_results.csv`: The results from the Bayesian Optimization process.
- `requirements.txt`: The required Python packages for reproducing the environment.

## Environment Setup

To run the notebook and use the trained model, you'll need to create a Python environment and install the necessary dependencies.

**Step 1: Clone the Repository**

Start by cloning this repository to your local machine:

```sh
git clone <repository-url>
cd <repository-directory>
```
Replace <repository-url> with the URL of this GitHub repository and <repository-directory> with the name of the directory where the repository is cloned.

**Step 2: Create and Activate the Environment**

Create a Python environment using Conda:
```sh
conda create --name sales_forecasting python=3.8
conda activate sales_forecasting
```

**Step 3: Install Dependencies**

Install the required Python packages using pip:
```sh
pip install -r requirements.txt
```

After installing the dependencies, launch Jupyter Notebook to open and run `analysis.ipynb`

Alternatively you can view the same file using https://jupyter.org/try-jupyter/lab/ 