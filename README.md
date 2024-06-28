# IBM Data Science Capstone Project - SpaceX

<img src="https://i.imgur.com/YCFnjvg.png" alt="Smiley face" height="300" width="600">

![IBM](http://i.imgur.com/Qktqnu1.png) INSTRUCTORS


# SpaceX Falcon 9 First Stage Landing Prediction

## Introduction

In this capstone project, our goal is to predict the successful landing of the Falcon 9 first stage. SpaceX promotes Falcon 9 rocket launches on its website, costing 62 million dollars, while other providers charge over 165 million dollars. A significant portion of the savings comes from SpaceX's ability to reuse the first stage. Thus, if we can predict whether the first stage will land successfully, we can estimate the launch cost. This information is crucial for another company looking to compete with SpaceX for rocket launch contracts.

This capstone project simulates a real-life data science experience, working with actual datasets. You will take on the role of a Data Scientist for a startup aiming to rival SpaceX. Throughout the project, you will follow the Data Science methodology, which includes [data collection](https://github.com/vishalorsu/IBM-Data-Science-Capstone-Project/blob/main/jupyter-labs-spacex-data-collection-api.ipynb), [data wrangling](https://github.com/vishalorsu/IBM-Data-Science-Capstone-Project/blob/main/labs-jupyter-spacex-Data%20wrangling.ipynb), [exploratory data analysis and data visualization](https://github.com/vishalorsu/IBM-Data-Science-Capstone-Project/blob/main/edadataviz.ipynb), [model development and evaluation](https://github.com/vishalorsu/IBM-Data-Science-Capstone-Project/blob/main/SpaceX_Machine%20Learning%20Prediction_Part_5.ipynb), and [reporting](https://github.com/vishalorsu/IBM-Data-Science-Capstone-SpaceX/blob/main/Winning%20Space%20Race%20with%20Data%20Science.pdf) your results to stakeholders. Your task is to predict the successful landing of the first stage of the SpaceX Falcon 9 rocket.

## Business Problem

SpaceX offers Falcon 9 rocket launches at a cost of 62 million dollars, compared to other providers' costs of over 165 million dollars. The savings largely come from the reuse of the first stage. Therefore, accurately predicting the likelihood of the first stage landing successfully will help determine the launch cost. Using the insights and models from your Data Science work, the startup you are working for can make more competitive bids against SpaceX for rocket launches.

## Objective

- Utilize data science tools and machine learning to accurately predict the likelihood of the first stage rocket landing successfully, thereby estimating the launch cost.
- Analyze the data to gain deeper insights.

## Methodologies

1. **Data Collection**: Data was collected from Open Source REST API for SpaceX and Wikipedia. The data was filtered to include only Falcon 9 launches, and missing payload mass values from classified missions were replaced with the mean.

2. **Data Wrangling**: Data exploration was conducted to create a training label for supervised models, categorizing the landing outcomes into classes based on the success or failure of the first stage booster landing.

3. **Exploratory Data Analysis (EDA)**: SQL queries were run to extract insights about launch sites, payload masses, booster versions, mission outcomes, and booster landings. Visualization tools like Matplotlib and Seaborn were used to plot various relationships and trends in the data.

4. **Data Visualization**: Launch sites were analyzed using interactive maps, and launch records were presented in a dashboard using Plotly Dash.

5. **Model Development**: Several machine learning models were developed and tested, including Logistic Regression, Support Vector Machine, Decision Tree Classifier, and K Nearest Neighbors Classifier. Hyperparameters were tuned using GridSearchCV, and models were evaluated based on their accuracy.

## Results

1. **Exploratory Data Analysis**: Specific queries were answered using SQL to provide insights into launch sites, payload masses, booster versions, and mission outcomes. Visualization of data showed trends and correlations, such as the positive correlation between continuous launch attempts and first stage landing success, and the negative correlation between payload mass and landing success.

2. **Launch Site Analysis**: Visualization of launch sites highlighted the importance of proximity to the coast and equator, with higher success rates at specific sites like KSC LC39A.

3. **Predictive Analysis**: The logistic regression model was highlighted for its accuracy in predicting the success of first stage landings, demonstrated through confusion matrices and other evaluation metrics.

## Deliverables

- Precise predictive algorithms
- A business case report for stakeholders

## Specialization Course Link

[IBM Data Science Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-science)

