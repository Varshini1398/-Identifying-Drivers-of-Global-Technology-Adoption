Project Overview
This project focuses on identifying the primary socio-economic drivers of technology adoption across major global economies, including India, the United States, the United Kingdom, the Russian Federation, China, and Japan.  The study uses applied econometrics and machine learning to bridge the gap between large-scale data and actionable research insights. The core objective is to model "Digital Inequality" by predicting national internet penetration rates based on infrastructure and human capital indicators. 
Technical Stack
•	Languages: Python
•	Libraries: pandas, numpy, scikit-learn
•	Methodology: Multivariate Regression
•	Tools: Jupyter Notebook, Excel
•	Visualization: Matplotlib

Dataset Specifications
•	Source: World Bank World Development Indicators
•	Target Variable: Individuals using the Internet (% of population)
•	Feature Variables: Access to electricity (% of population)
•	Educational attainment (at least Bachelor's or equivalent, population 25+)
•	Timeline of data: 2016 to 2025
Note: The project involves handling missing socio-economic data (indicated as ".." in raw sources) through professional statistical cleaning methods
Methodology: 
Predictive Modelling: Applying Multivariate Linear Regression to quantify the impact of electricity and education on digital adoption. Evaluation: Using the R-squared (R^2 metric to determine model accuracy)
Key Findings and Results
	The results imply a R-squared of 0.84, meaning the model explains 84% of the variance in global internet adoption
	The Actual vs. Predicted % Internet Users scatter plot demonstrates a strong linear correlation, with data points clustering closely around the red diagonal "perfect prediction" line. 
	Infrastructure (Electricity) serves as a fundamental prerequisite for digital access, while Human Capital (Education) significantly influences the depth of technology adoption within a population
	For example, as India’s electricity access reached 99.6%, its internet usage saw a dramatic rise to 60.2% by 2023
