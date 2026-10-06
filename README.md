# SpaceX Falcon 9 First Stage Landing Prediction

IBM Data Science Professional Certificate – Applied Data Science Capstone

## Project Overview
SpaceX advertises Falcon 9 launches at a much lower cost than competitors primarily due to first-stage booster recovery and reuse. For my capstone project, I built a complete end-to-end data science pipeline to predict whether a Falcon 9 first stage will land successfully. This repo covers everything from initial data collection and web scraping to EDA, interactive dashboards, and machine learning classification.

## Repository Contents

| # | File | Description |
|---|------|-------------|
| 1 | `jupyter-labs-spacex-data-collection-api.ipynb` | Collected launch data using the SpaceX REST API, filtered for Falcon 9, and cleaned missing payload values |
| 2 | `jupyter-labs-webscraping.ipynb` | Scraped historical Falcon 9 launch records and details from Wikipedia using BeautifulSoup |
| 3 | `labs-jupyter-spacex-Data_wrangling.ipynb` | Performed data cleaning, explored launch patterns, and engineered the binary landing target variable (`Class`) |
| 4 | `jupyter-labs-eda-sql-coursera_sqllite.ipynb` | Loaded data into SQLite and ran SQL queries to extract key database insights |
| 5 | `edadataviz.ipynb` | Conducted exploratory data analysis using Matplotlib and Seaborn, alongside feature one-hot encoding |
| 6 | `lab_jupyter_launch_site_location.ipynb` | Built interactive Folium maps to analyze launch site locations, clusters, and proximity metrics |
| 7 | `spacex-dash-app.py` | Developed an interactive Plotly Dash app featuring launch site selection and dynamic payload filtering |
| 8 | `SpaceX_Machine_Learning_Prediction_Part_5.ipynb` | Trained and hyperparameter-tuned multiple classification models (Logistic Regression, SVM, Decision Tree, KNN) |

## Key Results & Takeaways
- **Operational Growth:** Launch success rates improved significantly over time as flight numbers increased.
- **Site Performance:** KSC LC-39A demonstrated the highest overall launch success rate.
- **Model Performance:** Logistic Regression, SVM, and KNN all achieved strong test accuracies of 83.3%. While the Decision Tree scored high in cross-validation, it showed signs of overfitting on the test set.

## Tech Stack & Tools
Python, Pandas, NumPy, BeautifulSoup, SQLite, Matplotlib, Seaborn, Folium, Plotly Dash, Scikit-Learn
