# Shark Tank India Investment Analysis

**Repository Overview**

This repository explores the investment patterns of sharks on Shark Tank India. By analyzing investment data, we aim to uncover trends, preferences, and insights into the sharks' investment strategies.

## Data

The dataset includes comprehensive information about investments made by each shark:

- **Industry Sector**: The industry of the invested company.
- **Deal Size**: The total investment amount.
- **Equity Percentage**: The percentage of ownership acquired by the sharks.
- **Valuation**: The company's valuation at the time of investment.
- **Episode Details**: Information about the specific Shark Tank episode.
- **Shark Participation**: Which sharks participated in the deal.

Data is primarily in CSV format, cleaned, and preprocessed for analysis. You can find it in the [data](data/) directory.

## Methodology

Our analysis follows a structured approach:

1. **Data Cleaning and Preprocessing**: Handling missing values, inconsistencies, and outliers using scripts in the [scripts](scripts/) directory.
2. **Exploratory Data Analysis (EDA)**: Unveiling data distributions, correlations, and key trends using Jupyter notebooks in the [notebooks](notebooks/) directory.
3. **Investment Pattern Analysis**: Examining investment preferences based on industry, deal size, and equity percentage.
4. **Shark Performance Analysis**: Evaluating individual shark performance using metrics like ROI.
5. **Visualization**: Creating informative visualizations using Matplotlib and Seaborn to communicate findings effectively. Output plots are stored in the [visualizations](visualizations/) directory.

## Key Findings

- **Shark Investment Preferences**: Identifying preferred industries and deal sizes for each shark.
- **Investment Trends**: Analyzing overall investment trends across different seasons.
- **Successful Investment Patterns**: Discovering common characteristics of successful investments.
- **Shark Performance Comparison**: Comparing the investment performance of different sharks.


## Dependencies

To run the code, the following libraries are required:

- pandas
- numpy
- plotly

Install dependencies using `pip install -r requirements.txt`.

## Usage

To reproduce the analysis:

1. Clone the repository: `git clone https://github.com/yourusername/shark-tank-india-analysis.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Execute Jupyter notebooks in the [notebooks](notebooks/) directory.

