<img src='https://raw.githubusercontent.com/Milenaafeworki/Time-Series-prediction/main/images/SF.jpg'>

# Time series Prediction on California Home sales

With 54 of the Fortune 500 companies headquartered in California, like Google, Apple, Disney, Oracle and Intel among others, California is positioned for continued job growth. High employment rates draw renters and buyers and, for investors, enhance the likelihood of consistent cash flow. Though not the lowest in the country, California has favorable property tax rates, which will help control investors’ expenses and improve cash flow. The combination of job growth and a world-renowned lifestyle and culture supports home values. People buy where they want to live, and millions of people want to live in California. All of the demand mentioned above also leads to increasing home values.


## Business Problem

A real estate company is looking to flip homes, what are the top 5 zip codes to invest in? How will we scale our data? What defines best?

For this dataset, we will only include data from CA. Because of the housing market crash, any modelling that uses only recent years may be misleading. We will use every value from 1996 to 2018 so we can have the most accurate picture of home values in CA through the years.


## Data understanding

Zillow provides their users the opportunity to use their platform to access specific datasets for research purposes. The dataset that we will be using contains the median home sales prices throughout all states sorted by their zip codes. With this dataset we can extract a lot of insight through out all states with the potential to understand markets and develop investment strategies. This platform allows the public to do independent research in any market in the US.

This dataset contains 14723 rows and 272 columns.

## Methods

- CRISP-DM approach
- Return on Investment
- Risk to Reward ratio (Coefficient of variation)
- SARIMAX modeling
 
## Time series analysis

<img src='https://raw.githubusercontent.com/Milenaafeworki/Time-Series-prediction/main/images/ROI.png'>

<img src='https://raw.githubusercontent.com/Milenaafeworki/Time-Series-prediction/main/images/zip%20home%20value.png'>

## Recommendation
For the Real estate looking to immediately invest in the following zipcodes, here are the recommendations on the budget worth of a home and whether it is advisable to buy ,flip and sell the house, or buy and hold.

<img src='https://raw.githubusercontent.com/Milenaafeworki/Time-Series-prediction/main/images/Cali%20map.png'>


**Zip code 96141 (Placer county):** Buy, Flip and sell homes within a year. (Budget of $756,000)

                                
                                Total expected return in 1 year: 0.77%
                                Total expected return in 3 years: -3.8%                                
                                Total expected return in 5 year: -6.27%                                
                                Total expected return in 10 years: -8.15%
                                
                                
**Zip code 93405 (San Luis Obispo):** Buy and hold for the next 5-10 years. (Budget of $642,000)

                                  Total expected return in 1 year: 8.1%
                                  Total expected return in 3 years: 12.39%          
                                  Total expected return in 5 year: 13.0%
                                  Total expected return in 10 years: 13.13% 
                                  
                                  
**Zip code 92101 (San Diego county):** Buy and hold for the next 3-5 years. (Budget of $552,000)

                                   Total expected return in 1 year: 10.47%
                                   Total expected return in 3 years: 14.06%
                                   Total expected return in 5 year: 14.27%
                                   Total expected return in 10 years: 14.27%

                            
**Zip code 95441 (Sonoma County):** Buy, flip and sell within a year. (Budget of $684,000)

                                Total expected return in 1 year: 0.1%
                                Total expected return in 3 years: -7.26%
                                Total expected return in 5 year: -8.3%
                                Total expected return in 10 years: -8.42%
                                
**Zip code 91754 (Los Angeles):** Buy and hold for atleast 10years. (Budget of $587,000)

                              Total expected return in 1 year: 6.61%
                              Total expected return in 3 years: 15.09%
                              Total expected return in 5 year: 18.88%
                              Total expected return in 10 years: 21.05%

       
## Further Study

- The model is unable to correctly adjust to unique events such as exogenous data. Interest rates, rent values and GDP would be important factors to explore the relationship they would have with the home values. Rent income should exceed the costs of maintenance, mortgage, insurance, taxes and other expenses. Any gains that may be realized from selling the property later should also be factored into the calculation.


- Model would be more effective with more recent years data and considering the impact of recent events on Real Estate Business.
