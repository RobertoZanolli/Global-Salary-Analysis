# Global Salary Analysis Project

This project focuses on analyzing a global salary dataset, with the goal of exploring the distribution of average, minimum, and maximum salaries across various countries and continents. The analysis aims to uncover meaningful patterns by identifying countries with the greatest and smallest salary disparities, as well as those with the highest average and median salaries.

## Dataset

The dataset used in this project is **`salary_data.csv`**. It includes information on the average, minimum, and maximum salaries of different countries, categorized by continent.

## Project Objectives

- Identify the countries with the highest and lowest average and median salaries.
- Identify the countries with the greatest and smallest disparity between minimum and maximum salaries.
- Examine the salary distribution across different continents.

## Notebook

### `salary_analysis.ipynb`

This Jupyter notebook handles the import and analysis of the global salary dataset. It uses the **pandas**, **numpy**, and **matplotlib** libraries to perform the following tasks:

1. **Data preprocessing and loading**  
   - The dataset is loaded into a Pandas DataFrame for analysis.

2. **Exploratory data analysis (EDA)**  
   - Calculate the countries with the highest and lowest average and median salaries.  
   - Compute the salary disparity between the minimum and maximum salaries for each country.

3. **Data visualization**  
   - Create a histogram showing the distribution of average salaries across countries, ordered by the highest salaries.

## Script Functionality

- **Identify countries with the highest and lowest average salaries**  
  The script sorts countries by average salary and selects the top and bottom five.

- **Calculate salary disparity**  
  The script computes the salary disparity (difference between maximum and minimum salary) and identifies the five countries with the greatest and smallest disparities.

- **Visualization**  
  A bar chart is generated to display average salaries by country, providing a clear visual representation of global salary differences.

## Dataset Used

- The dataset is available on Kaggle: [Global Salary Data](https://www.kaggle.com/datasets/zedataweaver/global-salary-data).

## How to use the script

1. Clone the repository and open the notebook `salary_analysis.ipynb` in Jupyter Notebook.  
2. Run the notebook cells.
