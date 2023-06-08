# Correlation Analysis of University Rankings, GDP, and Population

## About the Project
This project aims to explore the relationships between university rankings, GDP (Gross Domestic Product), and population rank. By analyzing these correlations, we seek to gain insights into the potential impact of socioeconomic factors on university rankings.

## About the Data
The analysis utilizes several datasets collected from Kaggle:

- [**2020 University Rankings**](https://www.kaggle.com/datasets/erfansobhaei/ultimate-university-ranking) This dataset includes rankings from various sources such as CWUR, GreenMetric, Leiden, NatureIndex, Times, URAP, and Webometrics. It provides information on university ranks, institutions, locations, national ranks, quality of education, alumni employment, quality of faculty, research performance, and scores.

- [**World Population**](https://www.kaggle.com/datasets/iamsouravbanerjee/world-population-dataset) This dataset contains information on world population statistics for the year 2020. It includes country rankings, country/territory codes, country names, capital cities, continents, population figures for different years, area in square kilometers, population density, growth rate, and world population percentage.

- [**GDP (Gross Domestic Product)**](https://www.kaggle.com/datasets/rajkumarpandey02/list-of-countries-by-gdp-sector-composition) This dataset provides details on the GDP rank and GDP in millions of dollars for various countries and economies. It includes information such as index numbers, country/economy names, GDP breakdown by agriculture, industry, and services, and the percentage contribution of each sector to the GDP.

## Methodology
The project followed the following steps:

1. **Data Collection:** The datasets were obtained from Kaggle, ensuring comprehensive coverage of university rankings, GDP, and population rank.

2. **Data Cleaning and Preparation:** Thorough cleaning and preparation of the collected data were performed using Pandas and NumPy. This involved removing duplicates, handling missing values, and standardizing data formats to ensure data consistency.

3. **Data Integration:** The different datasets were merged based on common variables, such as university names and country names, to create a unified dataset for analysis.

4. **Calculation of Spearman Correlation Coefficients:** Spearman correlation coefficients were calculated using Pandas and NumPy. These coefficients measure the strength and nature of the relationships between university rankings, GDP, and population rank. Spearman correlation was chosen over Pearson correlation as it captures both linear and nonlinear relationships.

5. **Interpretation of Results:** The computed correlation coefficients were interpreted to understand the connections between university rankings, GDP, and population rank. The correlations were categorized as weak, moderate, or strong based on their magnitude and statistical significance.

## Libraries Used
The analysis utilized the following Python libraries:

- Pandas: For data cleaning, preprocessing, and merging.
- NumPy: For numerical computations and statistical analysis.
- Matplotlib & Seaborn: For creating the heatmaps and pairplots

Please refer to the project's [Jupyter notebook](https://github.com/enzopimentel/Uni-Rankin_GDP_World-Population_Correlation/blob/main/correlation.ipynb) for detailed code implementation and analysis.
