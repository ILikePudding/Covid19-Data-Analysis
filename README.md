# Group Project
Bao Khoi Bui (2060524), Aufstin Filiko (1638529), Shiv Vipulbhai Bardolia (2156848)
## Project Overview

This project explores the COVID-19 dataset to uncover trends, patterns, and anomalies during the pandemic, focusing on both the pre- and post-vaccination periods. By utilizing clustering techniques alongside exploratory data analysis (EDA), data preprocessing, and outlier detection, the project aims to identify meaningful insights into the effect of covid vaccines on the number of new cases, deaths, and hospitlization rates.

## Setup Instructions
Follow these steps to set up and run the notebook:

1. Ensure `owid_covid_data.csv` and the three accompanying jupyter lab notebooks `EDA.ipnyb`, `data_preprocessing.ipnyb`, and `outlier_detection.ipnyb` have been downloaded and are in the same folder space.

2. Ensure all prerequisites have been downloaded and there is a functioning instance of jupyterlab running.

3. Run the Notebook
- Open the command prompt and access the folder containing the files
- type/run : jupyter lab


This should open a local instance of jupyter lab and navigating to the project folder should allow access to and execution of all aforementioned notebook. The results in "Group Project Report" can be replicated by running each subscript.

## Components

1. **Exploratory Data Analysis (EDA)**:
   - Purpose: Visualize trends and correlations among key variables such as vaccination rates, hospitalization, mortality, and GDP.
   - Notebooks: `EDA.ipynb`
   - Tools: Scatterplots, regression lines, and binning to assist in visualization.

2. **Data Preprocessing**:
   - Purpose: Clean and transform raw data to prepare for analysis and modeling.
   - Notebooks: `data_preprocessing.ipynb`
   - Steps:
     - Categorized regions into Low, Medium, and High risk levels based on hospitalization rates.
     - Handled missing data and normalized key features.

3. **Clustering and Classification**:
   - Purpose: Identify significant features driving hospitalization trends and classify regions into risk levels.
   - Notebooks: `clustering.ipynb`
   - Models: Decision Trees, Random Forests.

4. **Outlier Detection**:
   - Purpose: Detect anomalies in COVID-19 metrics and contextualize them with real-world events.
   - Notebooks: `outlier_detection.ipynb`
   - Techniques: Z-Score, IQR (Interquartile Range), scatterplots for visualization.

5. **Report**:
   - Provides insight into the creating of the notebooks and the methodology behind the analysis. 
   - Documented figures, results, and conclusions from the project.
