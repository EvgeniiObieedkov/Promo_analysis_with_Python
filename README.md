Promo Campaign Revenue Analysis

The company specializes in monetizing travel-related content. Some users of the company's products can insert affiliate links into their blogs or articles. If a ticket is purchased through one of these affiliate links, both the user and the company receive a fixed percentage of the ticket price.

Affiliate Profit refers to the amount earned by the partner (the user).
Company Profit refers to the amount earned by the company.
Revenue = Affiliate Profit + Company Profit

From January 1 to April 2, 2023 (92 days), the company ran a promotional campaign for its users. During this period, users had a chance to win prizes. The winners were the 10 users who generated the highest number of bookings throughout the campaign.

The campaign aimed to re-engage inactive users and motivate new users to use affiliate links more actively. As a result, the total Revenue (i.e., the combined earnings from all partners over the campaign period) was expected to increase.

Key question:
Was the promotional campaign successful?
Was the goal of increasing total Revenue achieved?

Contents:
- Revenue_historical_data.csv – Daily revenue before the promotion
- Revenue_promo_data.csv – Revenue during the promotion
- Prophet model – Time series forecasting
- Outlier detection and smoothing using IQR + rolling average
- Stationarity check using the ADF test
- R² score to evaluate forecast accuracy
- Final comparison and conclusion

Method:
1. Clean and preprocess historical data
2. Remove outliers and smooth the series
3. Test for stationarity
4. Build a forecast model using Prophet
5. Predict revenue for the promo period
6. Compare actual promo revenue to forecasted values
7. Interpret results

Conclusion:
The model compares actual promo revenue with the upper bound of the Prophet forecast. If actual revenue exceeds the forecast, the campaign is considered successful.

