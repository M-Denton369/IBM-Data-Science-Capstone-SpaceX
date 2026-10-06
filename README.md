# SpaceX Falcon 9 First Stage Landing Prediction

IBM Data Science Professional Certificate – Applied Data Science Capstone

## Project Overview
SpaceX advertises Falcon 9 launches at a much lower cost than other providers, largely because the first stage booster can be recovered and reused. This project predicts whether the Falcon 9 first stage will land successfully, which helps estimate the cost of a launch. The analysis covers data collection, wrangling, exploratory data analysis, interactive visual analytics, and machine learning classification.

## Repository Contents

| # | File | Description |
|---|------|-------------|
| 1 | `jupyter-labs-spacex-data-collection-api.ipynb` | Collects launch data from the SpaceX REST API, filters to Falcon 9 launches, and handles missing payload values |
| 2 | `jupyter-labs-webscraping.ipynb` | Scrapes historical Falcon 9 launch records from Wikipedia with BeautifulSoup |
| 3 | `labs-jupyter-spacex-Data_wrangling.ipynb` | Explores launch sites, orbits, and outcomes, and creates the binary landing label (`Class`) |
| 4 | `jupyter-labs-eda-sql-coursera_sqllite.ipynb` | Exploratory data analysis with SQL queries on a SQLite database |
| 5 | `edadataviz.ipynb` | Exploratory data analysis with Matplotlib and Seaborn, plus feature engineering with one-hot encoding |
| 6 | `lab_jupyter_launch_site_location.ipynb` | Interactive launch site maps with Folium, including success markers and proximity distances |
| 7 | `spacex-dash-app.py` | Interactive Plotly Dash dashboard with a launch site dropdown and payload range slider |
| 8 | `SpaceX_Machine_Learning_Prediction_Part_5.ipynb` | Trains and tunes Logistic Regression, SVM, Decision Tree, and KNN classifiers with GridSearchCV |

## Key Results
- Landing success rates improved steadily over time as SpaceX gained operational experience.
- KSC LC-39A had the highest launch success rate of all sites.
- Logistic Regression, SVM, and KNN each reached 83.3% accuracy on the test set.
- The Decision Tree had the highest cross-validation score (90.4%) but the lowest test accuracy (66.7%), a sign of overfitting on the small dataset.

## Tools
Python, Pandas, NumPy, Requests, BeautifulSoup, SQLite, Matplotlib, Seaborn, Folium, Plotly Dash, Scikit-learn
