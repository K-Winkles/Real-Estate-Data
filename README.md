# Real-Estate-Data
A notebook containing analyses for real estate data from various countries.
# Context and Rationale
#### Source # 1: https://www.realestate.bnpparibas.com/how-data-science-transforming-real-estate

To summarize, real estate investors need to have data analyzed because of its business value. Real estate investment is a multi-million dollar investment vehicle and as such, serious practitioners have to deliberate every major move. 

On a consumer basis, Data Science and AI can provide the average person a concrete metric of what property would suit their needs the most. 

#### Source # 2: Private Real Estate Investment: Data Analysis and Decision Making by Roger J. Brown, Ph. D.

This book is available on Amazon.com and is free for Kindle Unlimited subscribers. Straight off the bat, this text is widely intended for investors and academics.

##### The first line reads "One of the oldest cliches we hear is: 'The three most important things in real estate are location, location, and location.'"

Apparently, the "Bid Rent Curve" means that the willingness of a renter to make a bid on the land depends on the land owners' ability to efficiently use the land (profitability).

To me, this means that the attractiveness of a piece of property hinges on profitability--which is directly influenced by location.

In CLASSICAL LOCATION THEORY, 

Rents will be highest where economic activity is the most intense and productive. 

Features include:

    1. Urban area is monocentric. I.e. Central business district with no residential areas
    2. Land is a flat plane 
    3. No input substitution or scale economies are possible
    4. Transportation costs are uniform in all directions
    5. The market is competitive. No monopoly.
## Rationale:
Given a sample listing, feed the data into my model and output the predicted price. 

This is loosely based on Niu and Niu's "An Intelligent Automatic Valuation System for Real Estate Based on Machine Learning" which can be found here: https://dl.acm.org/doi/abs/10.1145/3371425.3371454

I will be placing heavy emphasis on LOCATION, owing to the Bid Rent Curve and Classical Location Theory.

I will name this short study "Real Estate Valuation in Brazil using Keras"

Niu and Niu's methodology consists of 3 parts:
1. Repeated real estate recognition 
2. Feature engineering
3. Automatic Evaluation

Given the nature of the data set, I can skip right through # 1. For #2, Feature engineering, this is simply a matter of choosing relevant features. I will personally hand pick the features I would like to focus on. 

For #3, the authors implemented an Ensemble of models namely:
1. RF Algorithms (Random Forest)
2. GBDT (Gradient Boosting Decision Tree)
3. BP Neural Network (Back Propagation Neural Network)

Given the time frame, I will simply use Keras. If I decide to further pursue the study, I can definitely add more models.

#### References
https://www.kaggle.com/paultimothymooney/predict-california-housing-prices-with-tensorflow
https://www.tensorflow.org/tutorials/estimator/linear
https://www.tensorflow.org/tutorials/structured_data/feature_columns