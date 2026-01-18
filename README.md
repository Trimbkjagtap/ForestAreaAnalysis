# Forest Area Analysis

Analyze the changes in forest area over time and explore the impact of economic, demographic, and urbanization factors using data-driven methods and visualizations.

## Table of Contents
- [Forest Area Analysis](#forest-area-analysis)
  - [Table of Contents](#table-of-contents)
  - [Project Overview](#project-overview)
  - [Datasets](#datasets)
  - [Project Structure](#project-structure)
  - [Setup Instructions](#setup-instructions)
  - [Usage](#usage)
  - [Example Analysis](#example-analysis)

## Project Overview
This project investigates trends in forest area globally and regionally, correlating them with GDP per capita, population density, and urban expansion. The analysis is performed in a Jupyter Notebook and includes data cleaning, merging, visualization, and statistical insights.

## Datasets
- `forestation.csv`: Forest area data by country and year.
- `gdp-per-capita-maddison.csv`: Historical GDP per capita data.
- `population-density.csv`: Population density by country and year.
- `urban-area-long-term.csv`: Urban area expansion data.

## Project Structure
- `forest_area_analysis.ipynb`: Main Jupyter Notebook for analysis and visualization.
- `requirements.txt`: Python dependencies.
- `*.csv`: Data files used in the analysis.

## Setup Instructions
1. Ensure you have Python and Jupyter Notebook installed.
2. Install the required Python packages:
	```bash
	pip install -r requirements.txt
	```
3. Open `forest_area_analysis.ipynb` in Jupyter Notebook or VS Code.

## Usage
Run the notebook cells sequentially to:
- Load and clean datasets
- Merge and analyze data
- Visualize trends (e.g., forest area decline, GDP correlation)
- Draw insights from the results

## Example Analysis
The notebook provides:
- Line plots of forest area over time
- Correlation heatmaps between forest area, GDP, and population density
- Urbanization impact visualizations
- Statistical summaries and key findings
