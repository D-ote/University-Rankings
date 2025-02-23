# University Rankings (2016 - 2024)

[![image alt](https://github.com/D-ote/University-Rankings/blob/main/Screenshot%202025-02-23%20at%2011.53.55.png)](https://public.tableau.com/app/profile/dooter.ior/viz/UniversityRankings2016-2024/Dashboard2)

### Introduction
University rankings play a significant role in assessing the performance and reputation of higher education institutions worldwide. This report presents an analysis of a dataset containing various metrics used to rank universities, such as overall score, teaching quality, research environment, and others. Through exploratory data analysis (EDA) and predictive modeling, this analysis aims to uncover top factors influencing university rankings and build models to predict university rank categories.

The results of the analysis have been synthesized into an interactive dashboard hosted on Tableau Public, providing a user-friendly interface for exploring the findings. The dashboard includes geospatial visualizations, trend analyses, and comparative metrics across different regions, universities, and metrics.

[View the interactive dashboard on tableau public](https://public.tableau.com/app/profile/dooter.ior/viz/UniversityRankings2016-2024/Dashboard2)

### Project Objective
The primary objectives of this analysis are:

- To understand the factors influencing university rankings.
- To explore trends and patterns in university rankings over time.
- To identify the most influential features in predicting university rank categories.
- To build predictive models to classify universities into rank categories based on selected features.

### Data Source
The [dataset](https://www.kaggle.com/datasets/raymondtoo/the-world-university-rankings-2016-2024) is from kaggle.

### Research Questions
To achieve the objectives outlined above, the following research questions were addressed:

- Which countries have the highest number of universities represented in the dataset?
- What are the trends in overall score ranks of the top 7 universities over a 9-year period?
- How has the gender distribution of top universities changed from 2016 to 2024?
- What is the correlation between different metrics used in university rankings?
- Which features are most predictive of university rank categories?

### Data Preparation 
Before conducting the analysis, several data preprocessing steps were performed to ensure data quality and consistency:

Data Cleaning: The dataset was examined for missing values, duplicates, wrong data types, irrelevant columns, and inconsistencies, and appropriate measures were taken to handle them.
Feature Engineering: New features were created, such as gender distribution ratios and trend analysis variables, to facilitate analysis and modeling.
Exploratory Data Analysis: Descriptive statistics, visualizations, and correlation analysis were conducted to gain insights into the dataset's characteristics and relationships between variables.
Feature Selection: Relevant features were selected based on their correlation with university rankings and predictive power.

### Analysis
- Country Distribution: The analysis revealed the countries with the highest representation of universities in the dataset, providing insights into global higher education landscapes.
- Trend Analysis: Trend analysis of overall score ranks for the top 7 universities over a 9-year period highlighted fluctuations and patterns in university rankings over time.
- Gender Distribution: A comparison of gender distribution in top universities between 2016 and 2024 identified changes in gender representation trends within academic institutions.
- Correlation Analysis: Scatter plots and heat maps were used to visualize the correlations between different metrics, aiding in feature selection for predictive modeling.

### Model Building
- Machine Learning Models: Several machine learning algorithms, such as logistic regression, decision trees, and random forests, were trained on the dataset to predict university rank categories.
- Model Evaluation: Models were evaluated using performance metrics such as accuracy, precision, recall, and F1-score to assess their predictive performance.
- Feature Importance: Feature importance scores were calculated to identify the most influential features in predicting university rank categories.

### Conclusion
In conclusion, this analysis provides valuable insights into the factors influencing university rankings and presents predictive models for classifying universities into rank categories. By understanding these factors and leveraging predictive modeling techniques, stakeholders in the education sector can make informed decisions to improve university performance and enhance their global competitiveness.

### Limitations and Future Research
Limitations of this analysis include the reliance on available data and assumptions made during preprocessing and modeling. Future research could explore additional factors influencing university rankings, such as funding, student demographics, and alumni outcomes, to further enhance predictive models and decision-making processes.

Overall, this analysis contributes to the ongoing discourse on university rankings and demonstrates the potential of data-driven approaches to inform policy and practice in higher education.
