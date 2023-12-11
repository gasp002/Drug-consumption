# Final Project: Drug Consumption Analysis and Prediction


## Overview
This project develops a predictive model to identify the key factors influencing drug consumption. By analyzing various demographic, psychological, physical and educational factors attributes. It aims to understand their impact on the use of drugs like nicotine, alcohol,caffeine etc... The project not only delves into the statistical relationships between these factors and substance use but also attempts to predict usage patterns using machine learning techniques.

## Features
* Data Pre-Processing: Cleaning and organizing raw data to ensure accurate analysis.  
* Data Visualization: Creation of visual representations to explore the impact of factors such as gender, age, education, country, ethnicity and personality traits on drug use, and search for correlations between factors.  
* Data Prediction: Construction and evaluation of a predictive model to determine drug use patterns.  

## Tools and Technologies
* Python  
* Libraries: Pandas for data manipulation, Matplotlib, Seaborn and plotly for data visualization, Scikit-Learn for machine learning.  
* Jupyter Notebook  

## Installation and Usage
git clone [repository URL]  
cd [project directory]  
pip install -r requirements.txt  
jupyter notebook 'Final_project.ipynb'  
To launch the API, go into your CMD, cd to your repository, and launch python flaskpythonproject.py

## Data Source
The project utilizes data from "drug_consumption.data", which includes demographic and psychological profiles of individuals along with their drug use patterns. The data was found on this web site: https://archive.ics.uci.edu/dataset/373/drug+consumption+quantified

## Results and Discussion
The various models developed in this project demonstrate the complexity of predicting drug consumption. Key findings show the identification of the most influential factors in drug use and how these vary across different substances. The insights from this project can be valuable for public health interventions and understanding substance use behavior. In truth, our dataset was heavily biased towards a certain kind of person, because of this, it is complicated to create a predictive model that is accurate for any person in existence.
Although, we did our best by erasing some features that may not be relevant when predicting the frequency of usage of a certain drug. This led to having to use different models with different input features, with different parameters, for each drug. Yet our work was successful as we were able to build an API that would tell the user what are the chances they’ve used a drug or not in their life.

## Contributing
Contributions to this project are welcome. Please follow these steps:  
1. Fork the repository.  
2. Create a new branch for your feature.  
3. Commit your changes.  
4. Push to the branch.  
5. Create a new Pull Request.  

## Contact
* Project Maintainers: Adam NASSIR, Gaspard LUCIEN and Malvin NOËL  
* Email: adam.nassir@edu.devinci.fr, gaspard.lucien@edu.devinci.fr, malvin.noel@edu.devinci.fr  
* LinkedIn/GitHub: www.linkedin.com/in/gaspard-lucien-58a208208 https://www.linkedin.com/in/malvin-noel/ https://github.com/Niphto/FInalProjectPythonData

## Acknowledgments
Special thanks to https://archive.ics.uci.edu/dataset/373/drug+consumption+quantified for providing the dataset.


