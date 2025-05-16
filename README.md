#  COVID-19 Global Data Tracker

A data analysis project using Python and Jupyter Notebook to explore global COVID-19 trends over time, with a focus on confirmed cases, deaths, and vaccination data across countries and continents.

## Project Overview

This project analyzes real-world COVID-19 data from [Our World in Data](https://ourworldindata.org/coronavirus), specifically using the `Covid Data.csv` dataset. It provides insights through data cleaning, exploratory data analysis (EDA), and data visualization using `pandas`, `matplotlib`, and `seaborn`.

##  Objectives

- Import and clean COVID-19 data
- Analyze time trends for total cases, deaths, and vaccinations
- Compare metrics between selected countries (Kenya, USA, India)
- Visualize data with line plots and bar charts
- Summarize key insights from the data

## 📁 Dataset

**File:** `Covid Data.csv`

**Source:** [Our World in Data - OWID](https://ourworldindata.org/covid-cases)

**Key Columns:**
- `date`
- `location`
- `total_cases`
- `new_cases`
- `total_deaths`
- `new_deaths`
- `total_vaccinations`

##  Tools Used

- Python 3.x
- Jupyter Notebook (via Anaconda)
- pandas
- matplotlib
- seaborn

##  Steps Performed

1. **Data Loading & Exploration**
   - Load the dataset using `pandas`
   - Check for missing values and column types

2. **Data Cleaning**
   - Filter data for selected countries: Kenya, USA, India
   - Convert date columns to datetime
   - Handle missing numeric values

3. **Exploratory Data Analysis**
   - Plot total COVID-19 cases and deaths over time
   - Compare daily new cases
   - Calculate and analyze death rate

4. **Vaccination Analysis**
   - Plot cumulative vaccinations over time
   - Analyze percentage of population vaccinated


## 📈 Sample Visualization

![Sample Plot](./sample_plot.png) <!-- Optional: replace with actual plot -->

## 🧠 Key Insights

- India had the highest number of total cases among the selected countries.
- Kenya's vaccination rollout was significantly slower in the early months.
- The USA showed multiple waves in daily new cases.

## 📦 How to Run

1. Install [Anaconda](https://www.anaconda.com/products/distribution)
2. Launch Jupyter Notebook
3. Open the notebook file: `covid-19-continents-in-relation-to-time.ipynb`
4. Run all cells to view analysis and visualizations

## 📄 License

This project is for educational purposes. Data is sourced from publicly available sources via [OWID](https://ourworldindata.org/).

---

