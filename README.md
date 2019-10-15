# Analyzing Airbnb data for Boston and Seattle
Descriptive analysis of Airbnb data from Seattle, Boston

### Used libraries:
- collections
- matplotlib
- numpy
- pandas
- scipy
- seaborn
- sklearn
- warnings

### Version:
- Python 3.7
- Anoconda 1.9.7
- Jupyter 6.0.0

### CRISP-DM
Business Understanding: This data contain a lot of parameters related to Boston and Seattle Airbnb data.
#### Three Queations
1. I will use the data to find out some main factors that affect the price
2. Find a good model to predict the socre
3. What should a host do to improve the score(review_scores_rating) of his house from this model；

### Files
Major file is a Notebook for Analyzing airbnb data for Boston and Seattle. 

finalized_model.sav: the decision tree regressor we obtained with all features

deploy_model.sav: model with only 9 features

airbnb_regressor: dot file that shows structure of decision tree regressor
