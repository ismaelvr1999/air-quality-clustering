# Air Quality Clustering 🌬️
This project focuses on analyzing air quality data and categorizing it into clusters using the K-Means algorithm.

# Table of Contents 📚
- [Overview 🌟](#Overview-)
- [Technologies Used 🔧](#Technologies-Used-)
- [Dataset 📊](#Dataset-)
- [Data Preprocessing 🛠️](#Data-Preprocessing)
- [Clustering 📍](#Clustering)
- [Usage 🚀](#Usage-)
- [Author ✍️](#Author)
- [Acknowledgments 🙏](#Acknowledgments-)


## Overview 🌟

This project involves analyzing and clustering air quality data using the K-Means algorithm. The goal is to identify patterns and group similar data points based on various air quality metrics. We use different scaling techniques and compare the results to determine the optimal number of clusters.
## Technologies Used 🔧

This project utilizes the following technologies:
- **Python** 🐍: Programming language used for data analysis and machine learning.
- **Jupyter** 📓: Tool for creating and sharing documents with live code, equations, visualizations, and narrative text.
- **Libraries**:
  - **Pandas** 📊: Data manipulation and analysis library.
  - **Matplotlib** 📈: Plotting and visualization library.
  - **Scikit-learn** 🤖: Machine learning library for implementing K-Means and other algorithms.

## Dataset 📊

The dataset used is from the air quality measurements in the metropolitan area of Guadalajara, collected hourly throughout the year 2016 . It includes various columns related to air quality and environmental factors.

### Data Description

- **Date**: The date when the air quality data was recorded.
- **Time**: The time when the air quality data was sampled.
- **CO**: Carbon Monoxide.
- **NOX**: Nitrogen Oxides.
- **NO**: Nitric Oxide.
- **NO2**: Nitrogen Dioxide.
- **O3**: Ozone.
- **PM10**: Particles smaller than 10 micrometers.
- **SO2**: Sulfur Dioxide.
- **Temperature**: Temperature.
- **Relative Humidity**: Relative humidity present in the environment at that time.
- **Wind Speed**: Wind speed present at that time.
- **Wind Direction**: Wind direction present at that time.
- **Solar Radiation**: Solar radiation present at that time.

## Data Preprocessing

1. **Cleaning Data**: Removed duplicate records and records with missing values. Values marked as 'ND' were replaced with `None`.
2. **Sample Extraction**: Extracted a sample of data by selecting two records per day with the highest and lowest averages of chemical compounds.
3. **Dataset Preparation**: Created datasets with the relevant variables for training, including standardizing and scaling the data.
## Clustering📍

1. **K-Means Implementation**: 
   - Applied the K-Means algorithm to the dataset.
   - Used the elbow method to determine the optimal number of clusters.

2. **Comparison**:
   - Compared clustering results using all 7 variables versus using only NOX and CO.
   - Visualized clusters for both cases to analyze the differences.
## Usage 🚀

To run the project and perform clustering, follow these steps:
1. **Clone the Repository**:
   ```bash
   https://github.com/ismaelvr1999/air-quality-clustering.git
2. **Install Dependencies:**:
    ```bash
    pip install -r requirements.txt
## Author

- [@ismaelvr1999](https://www.github.com/ismaelvr1999)
## Acknowledgments 🙏

- **Dataset source**: [Jalisco Government Data](https://datos.jalisco.gob.mx/dataset/bases-de-datos-historicas-de-la-calidad-del-aire)

