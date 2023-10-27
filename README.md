# U.S.PublicHealthMetricsAnalysis_SQL

# Introduction
This project presents a comprehensive SQL data analysis of health metrics across various cities in the United States. While there's no specific business goal or predefined requirements, the analysis encompasses a broad exploratory approach. Delved into multiple aspects of the data to extract meaningful insights. Additionally, a visually engaging dashboard has been crafted to facilitate data exploration and provide an intuitive representation of findings.

## Contents
- [Dataset Information](#dataset-information)
- [Files in the Repository](#files-in-the-repository)
- [Tools Used](#tools-used)
- [Author](#author)

## Dataset Information:
- **Primary Dataset:** The main dataset used in this project is "BigCitiesHealth.csv."
- **Source:** You can find this dataset on Kaggle at [Big Cities Health Inventory (BCHI) Data](https://www.kaggle.com/datasets/venkateshseetha/big-cities-health-inventory-bchi-data/data) or within this repository.  
- **About the Dataset:**
The dataset consists of data from various cities in the United States, covering a wide range of health-related metrics. These metrics include information on access to healthcare, infectious diseases, and more. Additionally, the dataset provides data on population and poverty levels.

## Files in the Repository:
- [**BigCitiesHealth.csv**](BigCitiesHealth.csv): The main dataset.
- [**DataCleaningandPreparation.pdf**](DataCleaningandPreparation.pdf): An overview of data cleaning and preparation steps, including table creation, data import, handling of approximate location data, addressing missing values, data transformation, and normalization.
- [**healthcare_data_clean.csv**](healthcare_data_clean.csv): The dataset exported from the database after cleaning operations.
- [**DataAnalysis.pdf**](DataAnalysis.pdf): Provides insights into the dataset, explores relationships between health metrics, and ranks health metrics based on normalized values in different contexts. These findings are vital for further research and decision-making.  
**Note**: The outputs presented here are partial samples. For the full results, it is recommended to execute the queries locally to access complete findings.
- [**Sql_queries.txt**](Sql_queries.txt): Contains all SQL queries used in data cleaning and analysis. Feel free to use them locally for your analysis.
- [**U.S. Public Health Metrics Dashboard.png**](U.S.-Public-Health-Metrics-Dashboard.png):This dashboard leverages the dataset to provide visual insights, presenting data in five distinct visuals:  
**Categories:** The dashboard categorizes data for clarity and organization.  
**Metrics:** Metrics within each category are presented using a stacked bar chart.  
**State Data:** Geographic distribution and information are visualized through maps.  
**10-Year Trend:** The dashboard charts a 10-year trend of metrics using a line chart.  
**City Data:** City-specific details, including state, poverty level, population density, and average percentage, are presented in a concise table.  
For a detailed exploration of these visuals, you can access the [U.S. Public Health Metrics Dashboard](https://public.tableau.com/app/profile/sai.manoj.p7063/viz/U_S_PublicHelathMetricsDasboard/U_S_PublicHealthMetricsDashboard?publish=yes) directly.

## Tools Used

- **PostgreSQL:** Utilized for data cleaning and analysis.
- **Tableau:** Employed for data visualizations.

## Author
**Sai Manoj Pandiri**
- [GitHub](https://github.com/SAI-MANOJ-P)
- [Linkedin](https://www.linkedin.com/in/saimanojpandiri/)
