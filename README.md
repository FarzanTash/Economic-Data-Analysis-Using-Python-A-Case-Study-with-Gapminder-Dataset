# Economic-Data-Analysis-Using-Python-A-Case-Study-with-Gapminder-Dataset

## Project Overview

This repository contains a data science project aimed at analyzing various economic indicators using a dataset derived from Gapminder. The project showcases data cleaning, visualization, and statistical analysis techniques using Python libraries such as pandas, matplotlib, and plotly. The primary goal of this project is to provide insights into global economic trends and explore relationships between key economic variables.

## Dataset Description

The dataset used in this project is derived from Gapminder and contains economic indicators for various countries over multiple years. The dataset includes the following columns:

- `Country Name`: The name of the country.
- `Year`: The year of the observation.
- `Agriculture, value added (% of GDP)`: The contribution of agriculture to the GDP.
- `CO2 emissions (metric tons per capita)`: CO2 emissions per capita.
- `Domestic credit provided by financial sector (% of GDP)`: Credit provided by the financial sector as a percentage of GDP.
- `Electric power consumption (kWh per capita)`: Electric power consumption per capita.
- `Energy use (kg of oil equivalent per capita)`: Energy use per capita.
- `Exports of goods and services (% of GDP)`: Exports as a percentage of GDP.
- `Fertility rate, total (births per woman)`: The fertility rate.
- `GDP growth (annual %)`: Annual GDP growth rate.
- `Imports of goods and services (% of GDP)`: Imports as a percentage of GDP.
- `Industry, value added (% of GDP)`: The contribution of industry to the GDP.
- `Inflation, GDP deflator (annual %)`: Annual inflation rate.
- `Life expectancy at birth, total (years)`: Life expectancy at birth.
- `Population density (people per sq. km of land area)`: Population density.
- `Services, etc., value added (% of GDP)`: The contribution of services to the GDP.
- `pop`: Population.
- `continent`: Continent of the country.
- `gdpPercap`: GDP per capita.

## Project Steps

1. **Importing Libraries and Cleaning the Dataset**:
    - Installed and imported necessary libraries such as pandas, scipy, and plotly.
    - Loaded the dataset and performed initial data cleaning, including dropping unnecessary columns and handling null values.

2. **Exploratory Data Analysis (EDA)**:
    - Conducted EDA to understand the distribution and relationships of various economic indicators.
    - Visualized data using plotly to create interactive plots.

3. **Statistical Analysis**:
    - Performed statistical tests such as Pearson correlation, ANOVA, and t-tests to analyze relationships between variables.
    - Derived insights from statistical analysis to understand significant economic trends.

4. **Visualization**:
    - Created visualizations to represent the findings, including scatter plots, bar charts, and line graphs.

## Relevance to Data Science and Economics

This project is relevant to both data science and economics in several ways:

- **Data Science**: It demonstrates the application of data cleaning, exploratory data analysis, and statistical testing, which are fundamental skills in data science. The use of libraries like pandas and plotly highlights the importance of these tools in handling and visualizing data.

- **Economics**: The analysis of economic indicators such as GDP growth, CO2 emissions, and life expectancy provides valuable insights into global economic trends. By understanding these relationships, economists can make informed decisions and predictions about economic policies and development.

## How to Use This Repository

1. **Clone the repository**:
    ```sh
    git clone https://github.com/FarzanTash/Economic-Data-Analysis-Using-Python-A-Case-Study-with-Gapminder-Dataset.git
    ```
2. **Navigate to the project directory**:
    ```sh
    cd Economic-Data-Analysis-Using-Python-A-Case-Study-with-Gapminder-Dataset
    ```
3. **Install the required libraries**:
    ```sh
    pip install -r requirements.txt
    ```
4. **Run the Jupyter Notebook**:
    Open `code for the project.ipynb` using Jupyter Notebook to explore the analysis.

## Conclusion

This project serves as a comprehensive example of how data science techniques can be applied to economic data to derive meaningful insights. It demonstrates the power of Python in handling, analyzing, and visualizing complex datasets, making it a valuable resource for both data scientists and economists.
