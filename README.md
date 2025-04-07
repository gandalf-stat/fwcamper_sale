# fwcamper_sale
Notebook to estimate best asking price for four wheel camper sale.

# Analysis
The analysis is found in the notebook "market_analysis.ipynb" and consists of a simple additive linear model based on ads for four wheel campers on 2025-04-05. Note that the target variable is the asking price not sale price. In other words the final prediction can be used to set a new ad price but it shouldn't expected to predict the price at which the camper/rig will sell for.

# Data
The data is based on ads found "main line overland" and "facebook - used four wheel pop-up campers", and "kelly blue book" on 2025-04-05 and can be found in files "market_2025-04-05.csv" (easier to work with) and "market_2025-04-05.xlsx" (for easier editing). Here the kelly blue book was used to estimate the value of the trucks when the ad is for a truck/camper combo). To keep things simple when accounting for truck value, I simply found the kkb estimated value and confidence interval a add an observation for the lower bound, mean, and upper bound.


