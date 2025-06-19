# DATA11001 Introduction to Data Science Project

**Google Trends and COVID: Predictions and Correlation**

Welcome to the "Google Trends and COVID" project — an exploration of how Google search behavior correlates with COVID-19 case trends. The goal was to evaluate whether search volume data could serve as an early indicator for rising case numbers. This project was developed as part of the **DATA11001: Introduction to Data Science** course at the **University of Helsinki**.

---

### Project Highlights

- Correlated Google Trends keywords with COVID-19 case data using time-lag analysis  
- Identified the most predictive search terms through feature selection  
- Built and evaluated a machine learning model to forecast case trends  
- Transitioned from daily to weekly data for improved signal quality and prediction accuracy

---

### Tools & Libraries

- **Python**, **Jupyter Notebooks**  
- **pandas**, **NumPy**, **scikit-learn**, **pytrends**  
- Data sources: *Google Trends*, *Our World in Data*

---

### Files and Structure

**`data/`**  
- `owid-covid-data.csv`: COVID-19 case data from *Our World in Data*  
- `google_trends/`: Weekly search trends for selected keywords  
- `pytrends_data/`: Archived daily trends data used during initial exploration  
- `cleaned_data/`: Preprocessed datasets and intermediate outputs  

**`final project.ipynb`**  
Main notebook covering the full workflow:  
- Data loading & cleaning  
- Keyword correlation analysis  
- Model training and evaluation  

**`pytrends.ipynb`**  
Initial exploratory notebook using daily trends data before moving to weekly trends and lag analysis.
