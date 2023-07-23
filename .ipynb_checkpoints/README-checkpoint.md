# Portfolio Analysis: Cryptocurrencies
The aim of this project is to use unsupervised learning to create a crypto portfolio. The goal is to propose a well performing crypto portfolio to a top financial advisory firm's board of directors that is not purely based on only returns and volitility.

## About
Competition within Financial advisory firms is fierce. This project will analyze the cryptocurrency market to determine possible investment portfolios. The main Python functions that will be used are KMeans, PCA and StandardScaler from the scikit-learn package. The StandardScaler function will allow each factor to be normalized for the algorithm to create the model. The PCA function will allow multiple factors to be reduced to a much more manageable number. The KMeans function will be used to create the model and predict the clusters of cryptocurrencies with similar properties. This will ultimately determine a group of cryptocurrencies that perform better than others.

## Getting Started
To run the Jupyter notebook and interact with the visualizations and models, you need to have the following software and Python libraries installed:

- Python 3.10 or later
- Anaconda Distribution
- Pandas
- hvPlot
- scikit-learn

## Installing
1. Install the latest verion of Python [here](https://www.python.org/downloads/).

2. Install the latest version of Anaconda [here](https://www.anaconda.com/download).

3. Installing Anaconda includes the Pandas package.

4. To install the hvPlot and scikit-learn packages, run the following command in your terminal.

```
conda install -c hvplot
pip install -U scikit-learn
```

## Usage
You can clone or download this GitHub project and open the `crypto_investments.ipynb` using Jupyter Notebook. The Jupyter Notebook is seperated into sections that cover different aspects of the analysis. Each section contains explanations, code snippets, and interactive visualizations. By executing each cell in the Jupyter Notebook you can then interact with the visualizations.

## Contributor
Andy Vu