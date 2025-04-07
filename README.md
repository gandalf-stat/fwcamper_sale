# fwcamper_sale
Notebook to estimate asking price for a Four Wheel Camper sale.

# Analysis
The analysis is in the notebook "market_analysis.ipynb" and consists of a simple additive linear model based on ads for Four Wheel campers active as of 2025-04-05. Note that the target variable is the asking price, not sale price. In other words, the final prediction can be used to set a new ad price but it should not be expected to predict the price at which the camper/rig will sell.

# Data
The data is based on ads found on "main line overland" and "facebook - used four wheel pop-up campers", as well as "kelley blue book" data as of 2025-04-05 and can be found in files "market_2025-04-05.csv" (easier to work with) and "market_2025-04-05.xlsx" (for easier editing). The Kelley blue book was used to estimate the value of the trucks when the ad was for a truck/camper combo). To keep things simple when accounting for truck value, I simply found the kkb estimated value and confidence interval and added an observation for each of the lower bound, mean, and upper bound.
