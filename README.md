# Digital Awareness Analysis Using Machine Learning

This project focuses on creating digital awareness by analyzing the factors that influence the popularity of YouTube channels. By examining key features of these channels, we aim to understand the patterns that drive viewership and engagement in the digital sphere. A Linear Regression model is implemented to predict subscriber counts based on multiple channel characteristics.

## Table of Contents
    * Project Overview
    * Dataset Description
    * Data Preprocessing
    * Exploratory Data Analysis
    * Modeling
    * Results and Findings

## 1. Project Overview
In today’s digital landscape, understanding what drives users to certain types of online content is crucial for fostering a culture of informed digital engagement. This project uses machine learning to analyze the characteristics of popular YouTube channels, providing insights into how content preferences are shaped by factors such as category, video count, and total views. The ultimate goal is to promote digital awareness and encourage conscious online behavior.

## 2. Dataset Description
** The dataset contains insights into YouTube channels with the highest subscriber counts. It includes seven features for each channel, reflecting various metrics that potentially influence viewership trends:

- Rank: The rank of the channel based on its subscriber count.
- Youtuber: The official name of the YouTube channel.
- Subscribers: The total number of subscribers to the channel.
- Video Views: The cumulative view count across all videos on the channel.
- Video Count: The number of videos uploaded by the channel to date.
- Category: The genre or type of content (e.g., entertainment, education) that the channel specializes in.
- Started: The year in which the channel was launched.
This dataset allows us to analyze trends in digital engagement and viewer behavior based on channel popularity.

** Dataset taken from kaggle environment.

Source:  https://www.kaggle.com/datasets/surajjha101/top-youtube-channels-data
## 3. Data Preprocessing
** Several preprocessing steps were applied to ensure data quality and prepare it for analysis:

- Missing Value Handling: Checked for missing values to ensure data completeness.
- Data Type Conversion: Converted column data types where necessary to facilitate analysis.
- Feature Scaling: Standardized numerical features to improve model performance and ensure consistency.
- These steps were critical in creating a clean and usable dataset for effective model training.

## 4. Exploratory Data Analysis
* A comprehensive EDA was conducted to uncover insights and relationships within the data:

* Distribution Analysis: Visualized the distribution of subscribers, video views, and video count to understand the spread and central tendencies.
* Correlation Matrix: Examined correlations between features to determine which ones most significantly impact subscriber counts.
* Category Analysis: Analyzed subscriber counts and views by category to identify the most popular genres on YouTube.
* The insights obtained from EDA informed feature selection and guided our approach in building the regression model.

## 5. Modeling
We implemented a Linear Regression model to predict the number of subscribers based on the available features. This model was selected due to the anticipated linear relationship between channel attributes and subscriber count.

## 6. Model Training
- Train-Test Split: The data was split into training and testing sets to evaluate model performance.
- Hyperparameter Tuning: Optimal parameters were identified to enhance the model’s predictive accuracy.
- Model Evaluation : To assess the model’s effectiveness, we used the following evaluation metrics:

  ** `Mean Squared Error (MSE):` Measures the average squared difference between predicted and actual subscriber counts.

  ** `R-Squared (R²):` Indicates the proportion of variance in subscriber counts explained by the model.
 These metrics confirmed that the model provides valuable predictions, highlighting factors that influence channel popularity.

## 7. Results and Findings
** The Linear Regression model yielded significant insights into how different features impact subscriber counts. Notably:

* Video Views had the strongest positive correlation with subscriber counts, suggesting that viewer engagement directly contributes to channel growth.
* Content Category: Channels in certain categories, like entertainment and education, showed higher subscriber counts, pointing to popular viewer preferences.
* Video Count: Although video count had a positive correlation, it was weaker than views, indicating that content quality (views) may matter more than quantity.
* These results provide actionable insights for content creators and highlight key factors that shape digital consumption patterns.

