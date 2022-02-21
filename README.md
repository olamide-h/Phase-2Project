# Phase-2Project
![alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c5/HGTV_US_Logo_2015.svg/1200px-HGTV_US_Logo_2015.svg.png)
Authors: Olamide Olayinka, Ilene Sorto, Dara Estrada


# Business Problem
The cable television channel HGTV is in the beginning stages of researching a pilot episode for a new renovation series. 
Each episode will feature a different county in popular regions throught the United States. 
The first episode is slated to focus on the Pacific Northwest region, specifically within the Seatle metropolitan area of King County, Oregon. 
Due to the network's aversion to financial risk our data science team was contracted to provide an objective, outside analysis on the best ways to mitigate risk moving forward. Ultimately, the goal of the show is to tell homeowners what improvements to make on an objective and data driven level, for how to increase the value of their house so the owner can maximize value during sale. HGTV will be investing a percentage of renovations and wants to see the factors that would maximize return on their profits.SInce we are intrested in figuring out the maximizing the price of these houses, we selecetdd that our target. With this as our target,  we utilized several variables and analyzed their impact on predicting the price of homes in the county.
 
# Data
Our data was pulled forom the King County House Data: which contains homes built within the county from 1900 until 2014 in Kings County, Seattle. From there we noticed houses with multiple entries in the data set due to rennovations. We decided to drop these houses as to add clarity to the dataset. As we want to ensure for our stakeholder, that we are using rlevant information in our modeling process.  Futhermore, we noticed that a large amont of houses had no entires on whether or not they were on the waterfront. To ensure of data was more accurate, we had the missing entries fillied with 0 value. We deemed the variables with the most importance to our stakeholder to be the following : bedrooms, bathrooms, Sqft(Square Feet) -Living , Sqft Lot, Year built, grade, floors. With grade being a catregorical value ranging from Poor to Mansion level housing, we decidie to have this one hot encode to fit our modeling. This allowed us to utilize all the variables relevant to our stakeholders ultimate request. 

# Methods
We utilized Scikit Learn. 

# Models
With model 1, we utilized the variables of bedrooms, bathrooms, floors, grade, square feet lving , square feet lot, and year built. With this we got an R-squared of .63. In addition, the root mean squared error is 211289. With this being the metric of error in our model, we demmed this as not a hug error dealing with real estate. Howver we want to explore other models. This model already outpreforms the base.

On model 2 , we explored bathrooms and bedrooms against target price. This brought our r-sqaured down to 2.79. Compared to our previous model, this underperformed. So we decidied to mo on to another model. 

With our third model we got a r-squared of .50. This model accounted for squarefoot living, square foot living-15 and sqaurefoot lot. AN improvement from our previous model but not as good as our first model. 


# Conclusion/Reccomendations
Ultimately we found that our model 1 had the best results for our stakeholder. With this model we factored in bedrooms, bathrooms, sqft- living, sqft-lot, year built, grade and floors to see its impact on the prices of houses within Kings county. With these findins, we advise hgtv to first rennovate lower graded homes. We belive that with investing in these homes, there is a great oppertunity for growth and maximizing investment. Futhermore, we advise investing in quality ammenities and building adequte living space within the homes. As this maximizies sales price. And lastly, we advise utilzing quality materials and contractors to ensure our homes are quality as this has an impact on the grade aof the house and the grade has been proven to have an impact on price.c 


# Navigation
Data Folder - 
Final Notebook
Presentation.pdf
README.md
