# Geomagnetic Analysis: Kp Index & Solar Events

This project explores the relationship between solar events (including CMEs, solar flares, HSS, and IPS events) and geomagnetic disturbances on Earth, measured by the Kp Index (2021-2024). The analysis includes data collection, preprocessing, exploratory visualizations, and statistical testing.

## Project Structure

* **CSV files** - Contain processed solar event and Kp Index data. All CSVs are used in the analysis notebook.
* **`kp_index_analysis.ipynb`** - The main Jupyter notebook. Includes:

  * Loading and merging datasets
  * Cleaning and preprocessing data
  * Feature engineering (CME speed, flare counts, HSS/IPS counts, etc.)
  * Exploratory data analysis: histograms, scatterplots, bar charts, heatmaps
  * Performing statistical tests: Mann-Whitney U, Pearson & Spearman correlations, regression analysis
  * Generating visualizations and insights on how solar events influence the Kp Index

  All graphs and analysis are already included, so you can view the results directly without rerunning the notebook.
* **`README.md`** - This file, describing the project.

## Requirements

To run the code, you will need the following Python packages:

* `requests` - fetching data from APIs
* `json` - handling JSON data
* `pandas` - data manipulation and analysis
* `numpy` - numerical computations
* `matplotlib` - plotting and visualization
* `seaborn` - advanced plotting
* `scipy` - statistical tests

## Installation

Install the required packages using:

```bash
pip install requests pandas numpy matplotlib seaborn scipy
```

## Usage

1. Ensure all CSV files are in the main repository folder.
2. Open `kp_index_analysis.ipynb` in Jupyter Notebook or JupyterLab.
3. Run the notebook cells to reproduce all graphs, statistical tests, and insights.



