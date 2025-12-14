# 🌆 Smart City AQI Prediction - Machine Learning Project

## 📋 Project Overview
This project implements a comprehensive machine learning solution for predicting Air Quality Index (AQI) in smart cities. It includes web scraping, data analysis, feature engineering, and predictive modeling to identify factors contributing to poor air quality.

## 🎯 Features
- **Real-time Data Collection**: Web scraping from WAQI API and weather sources
- **Data Processing**: Cleaning, outlier detection, and feature engineering
- **Exploratory Analysis**: Visualizations and correlation studies
- **Predictive Modeling**: Linear Regression vs Random Forest comparison
- **Feature Importance**: Identifying key pollution factors

## 📊 Dataset
- **Source**: WAQI API (World Air Quality Index)
- **Parameters**: AQI, PM2.5, PM10, NO2, O3, Temperature, Humidity
- **Location**: Karachi, Pakistan
- **Time Period**: Real-time and historical synthetic data

## 🛠️ Technologies Used
- **Python 3.8+**
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Web Scraping**: Requests, BeautifulSoup
- **Machine Learning**: Linear Regression, Random Forest

## 📈 Results
| Model | R² Score | RMSE | MAE | Status |
|-------|----------|------|-----|--------|
| Linear Regression | 0.0393 | 34.56 | 30.96 | Baseline |
| Random Forest | 0.4210 | 26.83 | 21.56 | **Best Model** |

### Key Findings:
1. **PM10** is the most significant predictor (37% importance)
2. **Random Forest** outperforms Linear Regression by 380%
3. **Temperature** and **humidity** show moderate correlations
4. **Weekends** have higher pollution levels

## 📁 Project Structure
