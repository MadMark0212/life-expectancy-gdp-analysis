# Life Expectancy and GDP: A Cross-Country Analysis

---

## Project Overview

This project explores the relationship between **Gross Domestic Product (GDP)** and **life expectancy at birth** across six countries using data from the **World Health Organization (WHO)** and the **World Bank**.

The objective is to evaluate whether economic development is associated with improved population health outcomes and to quantify this relationship through exploratory data analysis and visualization.

---

## Objectives

- Analyze trends in GDP and life expectancy over time  
- Examine the relationship between economic output and health outcomes  
- Compare distributions of life expectancy across countries  
- Identify correlations between GDP and life expectancy  
- Communicate insights through data visualization  

---

## Dataset Information

The dataset includes annual observations for six countries and contains the following variables:

| Column | Description |
|--------|-------------|
| Country | Name of the country |
| Year | Observation year |
| GDP | Gross Domestic Product (USD) |
| Life Expectancy | Life expectancy at birth (years) |

### Data Sources
- World Health Organization (WHO)  
- World Bank  

---

## Tools and Technologies

- Python 🐍  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## Methodology

The analysis follows a structured exploratory data analysis (EDA) workflow:

1. Data loading and cleaning  
2. Descriptive statistics  
3. Time-series trend analysis  
4. Distribution analysis  
5. Correlation analysis  
6. Cross-country comparative visualization  

---

## Key Visualizations

### Life Expectancy Over Time
![Life Expectancy Trend](images/life_expectancy_trend.png)

---

### GDP Over Time (Log Scale)
![GDP Trend](images/gdp_trend.png)

---

### GDP vs Life Expectancy
![GDP vs Life Expectancy](images/gdp_vs_life_expectancy.png)

---

### Distribution of Life Expectancy
![Violin Plot](images/life_expectancy_distribution.png)

---

## Key Findings

- Life expectancy increased consistently across all six countries over time.  
- GDP exhibited strong upward trends, though at varying magnitudes.  
- A positive correlation exists between GDP and life expectancy.  
- The relationship is non-linear, with diminishing returns at higher GDP levels.  
- Countries with lower GDP experienced larger marginal gains in life expectancy from economic growth.  

---

## Limitations

- GDP is an aggregate measure and does not reflect income inequality.  
- Life expectancy does not capture quality of life or morbidity.  
- Other determinants such as healthcare systems, education, and policy were not included.  
- The analysis is observational and does not imply causation.  

---

## Future Work

- Incorporate healthcare expenditure and education indicators  
- Expand dataset to include more countries and regions  
- Perform regression modeling and statistical hypothesis testing  
- Explore inequality-adjusted development indicators  

---

## Project Structure

life-expectancy-gdp-analysis/
│
├── data/
│ └── all_data.csv
│
├── images/
│ ├── life_expectancy_trend.png
│ ├── gdp_trend.png
│ ├── gdp_vs_life_expectancy.png
│ └── life_expectancy_distribution.png
│
├── notebooks/
│ └── life_expectancy_gdp.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore

---

## How to Run This Project

```bash
git clone https://github.com/yourusername/life-expectancy-gdp-analysis.git
cd life-expectancy-gdp-analysis
pip install -r requirements.txt
jupyter notebook

---
