<img src='https://raw.githubusercontent.com/Milenaafeworki/Time-Series-prediction/main/images/SF.jpg'>

# Time series Prediction on California Home sales

With 54 of the Fortune 500 companies headquartered in California, like Google, Apple, Disney, Oracle and Intel among others, California is positioned for continued job growth. High employment rates draw renters and buyers and, for investors, enhance the likelihood of consistent cash flow. Though not the lowest in the country, California has favorable property tax rates, which will help control investors’ expenses and improve cash flow. The combination of job growth and a world-renowned lifestyle and culture supports home values. People buy where they want to live, and millions of people want to live in California. All of the demand mentioned above also leads to increasing home values.


## Business Problem

A real estate company is looking to flip homes, what are the top 5 Zip codes to invest in? How will we scale our data? What defines best?

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

The home sale values have turned up to show that our 10 counties have had an ROI gain of at least 150% of their original value from 1996. With Placer, Orange county, San Luis Obispo and San Diego making it to above 250%. The zipcodes from these counties had been further filtered out according to their risk to reward ratio, and taking into consideration only the ones with values less than 35%.


<img src='https://raw.githubusercontent.com/Milenaafeworki/Time-Series-prediction/main/images/ROI.png'>


Looking at the trend Home prices crashed during and after The Great Recession, which started as a result of the subprime mortgages and mismanagement of mortgage-backed securities, which caused real estate housing prices to fall by 30% to 50% in a matter of months. The future’s unpredictability has also been taken into consideration to select zipcodes with resilience and better recovery history. The next step was to build models for each of the top10 zip codes and see how they would perform on predicting home prices for the next 10years.

<img src='https://raw.githubusercontent.com/Milenaafeworki/Time-Series-prediction/main/images/zip%20home%20value.png'>

## Recommendation

For the Real estate looking to immediately invest in the following Zip codes, here are the recommendations on the budget worth of a home and whether it is advisable to buy ,flip and sell the house, or buy and hold.

<img src='https://raw.githubusercontent.com/Milenaafeworki/Time-Series-prediction/main/images/Cali%20map.png'>



**Zip code 92866 (LA- Long Beach county):** Buy, Flip and sell homes within a year. (Budget of $584,000)

                                
                            Total expected return in 1 year: 2.5%
                            Total expected return in 3 years: 2.67%
                            Total expected return in 5 year: 2.67%
                            Total expected return in 10 years: 2.67%
                                
                                
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

                            
**Zip code 92860 (Riverside County):** Buy, flip and sell within a year. (Budget of $439,000)

                            Total expected return in 1 year: 7.43%
                            Total expected return in 3 years: 11.23%
                            Total expected return in 5 year: 11.82%
                            Total expected return in 10 years: 11.93%

**Zip code 91754 (Los Angeles):** Buy and hold for atleast 10years. (Budget of $587,000)

                            Total expected return in 1 year: 2.6%
                            Total expected return in 3 years: 4.72%
                            Total expected return in 5 year: 5.32%
                            Total expected return in 10 years: 5.54%

       

       
## Further Study

- Increase effectiveness of model with more recent years of data and examine how recent events such as COVID have impacted the Real Estate business.

- Explore how model would be able to adjust to exogenous data such as interest rate, rent values, GDP to further investigate their relationship with home values.

- Rent income should exceed the costs of maintenance, mortgage, insurance, taxes and other expenses. Any gains that may be realized from selling the property later should also be factored into the calculation.

```
├── images
├── notebook
├── time series analysis.pdf
├── time series analysis.ipynb
├── README.md
└── Zillow_data.csv
```


