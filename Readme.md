# Sugarcane Production Data Analysis

A comprehensive data analysis project examining global sugarcane production patterns using Python and data visualization libraries.

## Overview

This project analyzes sugarcane production data across different countries and continents, providing insights into production volumes, acreage, yields, and per-person production rates. The analysis includes data cleaning, exploratory data analysis, and visualization of key trends and relationships.

## Dataset

The analysis uses a CSV file containing sugarcane production data with the following key variables:
- **Country**: Country name
- **Continent**: Continental classification
- **Production (Tons)**: Total sugarcane production in tons
- **Acreage (Hectare)**: Land area used for sugarcane cultivation in hectares
- **Production per Person (Kg)**: Per capita production in kilograms
- **Yield (Kg / Hectare)**: Productivity per hectare

## Features

### Data Preprocessing
- Data cleaning and type conversion
- Handling missing values and null entries
- String formatting and numeric conversion
- Data validation and quality checks

### Univariate Analysis
- Distribution analysis of key production metrics
- Continental breakdown of sugarcane-producing countries
- Statistical summaries and descriptive statistics
- Visualization of individual variable distributions

### Bivariate Analysis
- Country-wise production comparisons
- Percentage contribution analysis with pie charts
- Top producer identification and ranking
- Cross-variable relationship exploration

### Correlation Analysis
- Comprehensive correlation matrix of all numeric variables
- Heatmap visualization of variable relationships
- Scatter plot analysis of key relationships
- Statistical correlation coefficients

### Continental Insights
- Continent-wise production aggregation
- Comparative analysis of regional performance
- Country count vs production relationship analysis
- Regional productivity patterns

## Technical Requirements

```python
pandas>=1.3.0
matplotlib>=3.5.0
seaborn>=0.11.0
numpy>=1.21.0
```

## Key Visualizations

1. **Distribution Plots**: Understanding the spread of production metrics
2. **Bar Charts**: Continental production comparisons
3. **Pie Charts**: Market share analysis by country
4. **Correlation Heatmap**: Variable relationship matrix
5. **Scatter Plots**: Acreage vs Production and Yield vs Production relationships
6. **Line Plots**: Country count vs production trends by continent

## Installation & Usage

1. Clone the repository or download the script
2. Ensure you have the required Python libraries installed:
   ```bash
   pip install pandas matplotlib seaborn numpy
   ```
3. Place your sugarcane production CSV file in the appropriate directory
4. Update the file path in the script: `df=pd.read_csv("your_file_path.csv")`
5. Run the script: `python sugarcane_production.py`

## File Structure

```
sugarcane-analysis/
│
├── sugarcane_production.py    # Main analysis script
├── Sugarcane Production.csv   # Dataset (not included)
├── README.md                  # This file
└── outputs/                   # Generated visualizations (created during execution)
```

## Key Insights

The analysis reveals:
- Global distribution of sugarcane production across continents
- Relationship between land usage (acreage) and total production
- Productivity efficiency measured by yield per hectare
- Per capita production patterns across different regions
- Market concentration and leading producer countries

## Data Quality Notes

- The script includes comprehensive data cleaning procedures
- Handles formatting inconsistencies in numeric fields
- Manages missing values appropriately
- Converts string representations to proper numeric formats

## Future Enhancements

- Time series analysis if historical data becomes available
- Economic analysis incorporating price and market value data
- Climate correlation analysis
- Predictive modeling for future production trends
- Interactive dashboard development

## Contributing

Feel free to contribute by:
- Adding new analysis features
- Improving visualizations
- Enhancing data preprocessing
- Adding statistical tests
- Improving documentation

## License

This project is open source and available under standard data analysis usage terms.

---

*Originally developed in Google Colab environment*