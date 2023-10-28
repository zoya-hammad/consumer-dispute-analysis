# Bank and Credit Card Complaints 🏦

Analysis of consumer complaints related to credit card companies. From data cleaning and visualization to training a classification model, here are some insights from my journey.

## Project Overview

- **Dataset Source**: Kaggle (https://www.kaggle.com/datasets/mexwell/bank-and-credit-card-complaints)
- **License**: CC0: Public Domain

## Key Insights

- **Most Complaints**: Citibank received the highest number of complaints among all institutions.
- **State with Most Complaints**: California (CA) had the highest number of reported complaints.
- **Prompt Resolutions**: An impressive 78.2% of complaints were resolved within a day.
- **Consumer Disputes**: Surprisingly, only 24.6% of consumers disputed the resolutions.
- **Max Resolution Time**: The maximum time difference between complaint and resolution was a staggering 257 days.

## Data Preprocessing

- **Cleaning**: I eliminated redundant data and removed columns with constant values.
- **Date Conversion**: I converted date strings to datetime objects for analysis.
- **Time Difference**: Calculated the time difference between complaint and resolution.
- **Null Value Handling**: Columns with null value percentages greater than 50% were removed.
- **Duplicates**: I addressed duplicates in the dataset and removed them.
- **Encoding**: Applied label and one-hot encoding to prepare data for modeling.
- **Value Cleanup**: Deleted rows with erroneous negative time differences.

## Data Visualization

- **Graphs**: My visualizations include bar charts and pie charts to highlight important trends and insights.
- **Correlation Matrix**: I analyzed the correlation matrix to prepare for classification.

## Classification Model
- **Classification Model**: I employed a Random Forest Classifier to predict consumer disputes and timely responses. 
- **Confusion Matrix**: My classification model offers predictive capabilities, and I evaluated its performance using a confusion matrix.

Explore, contribute, and use these insights to enhance your understanding of consumer complaints in the banking and credit card industry.

**Happy Analyzing!** 🚀
