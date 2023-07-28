# ELECTIONS

This GitHub repository contains Jupyter Notebook files for analyzing election data and visualizing various aspects of the data. The repository includes the following notebooks:

## visualize.ipynb
This notebook focuses on data visualization using a constituency map to represent party distribution. It utilizes Geopandas and Plotly Express libraries to display the party distribution across different constituencies. The code for the visualization is somewhat inefficient, so it may take time to run. 

## candidate_analysis.ipynb
In this notebook, pie charts are used to analyze criminal cases of candidates. It also includes pie charts to represent gender and education distribution among candidates. Similar pie charts are presented for the winning candidates.

## classification.ipynb
This notebook implements a classification model to predict whether a candidate is likely to win or not. It utilizes machine learning libraries such as Scikit-learn for model training and evaluation.

## Libraries Used
The following libraries are used in the notebooks:

- Pandas: Used for data manipulation and analysis.
- Matplotlib: Utilized for basic data visualization.
- Geopandas: Used for working with geospatial data, specifically to plot the constituency map.
- Plotly Express: Utilized for data visualization.
- Scikit-learn: Used for implementing the classification model.

## How to Run the Code
To run the notebooks in this repository, follow these steps:

1. Clone the repository to your local machine using `git clone https://github.com/JayMuppidi/ELECTIONS.git`.

2. Make sure you have Jupyter Notebook or JupyterLab installed on your machine.

3. Navigate to the cloned repository directory using the command line.

4. Launch Jupyter Notebook by running `jupyter notebook` or JupyterLab by running `jupyter lab`.

5. Before running the code, make sure you've installed all the required libraries, if not use the command below.

```bash
pip install pandas matplotlib geopandas plotly scikit-learn
```
## Data Sources
The shapefile for constituencies is obtained from datameet.org, and some data is from myNeta which analyzed candidate's affidavits and organized it.
