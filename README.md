**TAXI DATA ANALYSIS – PROJECT SUMMARY**

**Project**: Exploratory Data Analysis of Taxi Trips

**Tools Used**: Python, Pandas, NumPy, Matplotlib, Seaborn

**Introduction**

The main objective of this project is to analyze taxi trip data and identify useful patterns related to fares, trip distances, pickup locations, payment methods, and customer tipping behavior. The Seaborn built-in Taxi dataset was used for this analysis.

**Data Cleaning**

The dataset was loaded using Seaborn and examined using Pandas. Missing values were identified and handled using suitable techniques. Median imputation was applied to numerical columns, while mode imputation was used for categorical columns. Rows containing missing critical information were removed. The pickup timestamp was also converted into datetime format for time-based analysis.

**Data Visualization and Analysis**

Ten visualizations were created using Matplotlib and Seaborn:

**Line Chart:** Analyzed fare variations over pickup time.

**Bar Chart:** Compared total fare revenue across pickup boroughs.

**Pie Chart:** Examined customer payment method preferences.

**Histogram:** Studied the distribution of taxi trip distances.

**Box Plot:** Compared tip amounts across pickup boroughs.

**Count plot:** Identified the number of trips in each pickup borough.

**Scatter Plot:** Examined the relationship between distance and fare.

**Heatmap:** Identified correlations between distance, fare, tips, tolls, and total amount.

**Pair Plot:** Compared relationships between numerical variables across pickup zones.

**Violin Plot:** Examined fare distributions for different payment methods.

**Key Findings**

The analysis helped identify important patterns in taxi trip data.

Trip distance and fare were analyzed to understand how travel distance affects fare amounts.

Pickup borough comparisons helped identify areas with higher trip activity and total fare revenue.

Payment method analysis showed the distribution of cash and credit card transactions.

Tip distributions helped compare customer tipping behavior across boroughs.

Correlation analysis helped understand relationships between fare, distance, tips, tolls, and total amounts.

**Important Numerical Results:**

Total trips analyzed: 6433

Average fare: 09

Average trip distance: 02

Average tip: 98

Most common payment method: Credit Card

Most popular pickup borough: Manhattan

Highest revenue pickup borough: Manhattan

Distance and fare correlation: 0.92

**Conclusion**

This project demonstrates how Python libraries such as Pandas, Matplotlib, and Seaborn can be used to clean, analyze, and visualize real-world taxi data. The analysis provides useful insights into trip patterns, fare distributions, payment preferences, and customer behavior. These findings can help taxi service providers improve operational planning, understand customer preferences, and make better business decisions.
