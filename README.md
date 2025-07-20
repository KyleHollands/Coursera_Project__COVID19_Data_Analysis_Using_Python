# Coursera_Project__COVID19_Data_Analysis_Using_Python

## Project Overview
This project analyzes COVID-19 data using Python, focusing on how social and health indicators relate to infection and death rates across countries. The workflow includes:

- Importing and performing EDA on COVID-19 datasets to engineer features like "max_infection_rate" and "max_death_rate".
- Importing a happiness score dataset with social and health indicators.
- Merging datasets by country and visualizing relationships between indicators and COVID-19 rates.
- A correlation heatmap was generated to identify significant relationships.
- To ensure visualizations are clear, logarithmic transformations were applied to the data.
- Exploring how factors such as social support, healthy life expectancy, and freedom to make life choices correlate with COVID-19 outcomes.

## Data Understanding
The project uses three datasets:
1. **COVID-19 Confirmed Cases Data**: Contains daily infection rates for various countries.
2. **Happiness Score Data**: Includes social and health indicators for countries, such as social support, healthy life expectancy, and freedom to make life choices.
3. **COVID-19 Deaths Data**: Contains daily death rates for various countries.

The datasets are merged based on country names to facilitate analysis. The COVID-19 data is processed to calculate maximum infection and death rates, while the happiness score data provides insights into social indicators.

## Modeling and Evaluation
The project uses Python libraries such as Pandas, NumPy, and Seaborn for data manipulation and visualization. The analysis includes:
- Merging datasets on country names.
- Calculating maximum infection and death rates.
- Visualizing relationships using scatter plots and regression lines.
- Generating a correlation heatmap to identify significant relationships between social indicators and COVID-19 rates.

## Conclusion
The analysis shows that higher infection rates are strongly linked to higher death rates. Wealthier, healthier countries with strong social support tend to have higher reported infection and death rates, likely due to demographic and reporting factors. However, correlation does not imply causation—other factors may be influencing these relationships.