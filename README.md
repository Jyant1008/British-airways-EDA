
# British Airline Customer Behavior Analysis and Insights

## Project Overview

This project involves analyzing a dataset from a British airline to uncover customer behavior patterns and preferences. Using exploratory data analysis (EDA) and hypothesis testing, we aim to provide actionable insights for business decisions, such as enhancing customer satisfaction and optimizing marketing strategies.

## Dataset Description

The dataset contains various details about customer bookings, preferences, and flight information. Key columns include:

**Customer ID**: Unique identifier for each customer.
**
**Booking Completion:** Whether a customer completed their booking.

**Trip Type:** Categorized as "RoundTrip" or "OneWay".

**Flight Duration:** Duration of the flight in minutes.

**Booking Day Type:** Indicates if the booking day is a holiday or a regular day.

**Wants Extra Baggage:** Whether the customer opted for extra baggage.

## Key Objective

Perform EDA to understand customer behavior and booking patterns.

Use statistical hypothesis testing to validate insights derived from EDA.

Provide actionable recommendations based on findings.

## Exploratory Data Analysis (EDA)

Understanding Booking Trends: Analyzed booking rates across different day types (holidays vs. regular days).

Trip Type Distribution: Examined the proportion of round trips vs. one-way trips.

Flight Duration Insights: Investigated the distribution of flight durations.

Extra Baggage Preference: Studied the percentage of customers opting for extra baggage.

Visualization tools like bar plots, histograms, and pie charts were used to illustrate trends and distributions.

## Hypothesis Testing


### Hypothesis 1: Flight Duration by Trip Type

Objective: Assess whether average flight durations differ significantly between round trips and one-way trips.

Test: Independent T-Test.

Result: Significant difference observed (p-value < 0.05).

### Hypothesis 2: Extra Baggage Preference by Trip Type

Objective: Evaluate if customers' preference for extra baggage differs between round trips and one-way trips.

Test: Proportion Z-Test.

Result: No significant difference (p-value > 0.05).

## Tools and Libraries Used

Programming Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, SciPy, Statsmodels

## Key Insights and Recommendations

Holiday Promotions: Higher booking completion rates on holidays suggest targeted marketing campaigns during these times can be effective.

Flight Duration Awareness: Significant differences in flight durations for round trips vs. one-way trips could guide scheduling decisions.

Baggage Policies: Uniform baggage pricing is sufficient as no significant differences in preferences were observed.

## How to Run the Project

Clone the repository.

Run the Jupyter Notebook EDAproject.ipynb to view the analysis.

## Future Enhancements

Incorporate machine learning models for predicting booking completion rates.

Analyze additional customer demographics for more granular insights.

Explore time-series data for trends in customer bookings over time.

## Conclusion

This project provides a comprehensive analysis of customer behavior for a British airline, with actionable insights to improve business strategies and customer satisfaction. Further analysis and enhancements can lead to deeper understanding and optimization opportunities.

