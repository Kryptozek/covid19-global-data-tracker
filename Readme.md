# COVID-19 Global Data Tracker

## Project Description
This project provides a comprehensive data analysis and visualization of global COVID-19 trends. It tracks cases, deaths, recoveries, and vaccinations across countries and time periods, offering insights into the pandemic's global impact and the effectiveness of vaccination campaigns.

## Project Objectives
- Import and clean COVID-19 global data from reliable sources
- Analyze time trends for cases, deaths, and vaccinations
- Compare key metrics across different countries and regions
- Visualize trends with interactive charts and maps
- Provide data-driven insights about the pandemic's progression

## Tools and Libraries Used
- **Python**: Core programming language for the analysis
- **Pandas**: Data manipulation and analysis
- **Matplotlib & Seaborn**: Static data visualization
- **Plotly Express**: Interactive maps and visualizations
- **NumPy**: Numerical operations
- **Jupyter Notebook**: Interactive development environment

## How to Run/View the Project
This project can be run without any local installation using Google Colab:

1. Open the [COVID19_Global_Data_Tracker.ipynb](./COVID19_Global_Data_Tracker.ipynb) file in this repository
2. Click the "Open in Colab" button at the top of the file (or manually open [Google Colab](https://colab.research.google.com/) and upload the file)
3. Run each cell in sequence (Runtime → Run all)
4. All visualizations and analyses will be generated in your browser

## Key Insights and Findings
The analysis revealed several important insights about the global COVID-19 pandemic:

1. **Global Trends**: Multiple distinct waves of infections occurred globally, with significant increases during major variant outbreaks.

2. **Country Comparisons**: 
   - The United States, India, and Brazil had the highest absolute number of cases and deaths
   - When normalized by population, different patterns emerged, highlighting the importance of considering per-capita metrics
   - Death rates varied significantly between countries, suggesting differences in healthcare capacity, reporting standards, demographics, and intervention strategies

3. **Vaccination Impact**:
   - Countries with higher vaccination rates generally experienced lower death rates in later waves
   - There's a notable gap between countries with high vaccination rates (>70%) and those with lower rates (<30%)
   - Vaccination rollouts progressed at vastly different rates across countries

4. **Regional Variations**:
   - Different continents experienced peak waves at different times
   - Regional cooperation and geographic proximity influenced spread patterns

## Future Work
Potential extensions to this analysis could include:
- Incorporating mobility data to correlate lockdown measures with case trends
- Adding economic indicators to analyze socioeconomic impacts
- Examining healthcare system capacity correlation with outcomes
- Analyzing the effects of different variants on case fatality rates

## Data Source
Data for this project comes from [Our World in Data](https://ourworldindata.org/coronavirus), a trusted source for COVID-19 statistics.
