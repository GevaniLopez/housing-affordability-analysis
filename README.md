# Housing Affordability for First-Time Homebuyers Across U.S. States

## Project Overview
This project analyzes which U.S. states appear more affordable for first-time homebuyers by combining median household income, FHFA House Price Index data, and recent home price growth. Instead of looking at home prices alone, the project compares multiple factors together to show where affordability looks stronger or weaker at the state level.

## Business Question
Which U.S. states appear more affordable for first-time homebuyers when comparing income, home price growth, and overall housing affordability together?

## Why It Matters
Housing affordability is one of the biggest barriers facing first-time homebuyers. Looking at home prices alone does not tell the full story, because income levels and price growth also affect how realistic homeownership may be in different states. This project was built to create a clearer comparison using multiple factors instead of assumptions.

## Data Sources
- U.S. Census Bureau median household income data
- FHFA House Price Index data

## Tools Used
- Python
- pandas
- matplotlib
- scikit-learn
- Jupyter Notebook

## Approach
I cleaned and merged public state-level income and housing datasets in Python, created an affordability ratio, and used visual analysis to compare states. I also applied linear regression and K-means clustering to explore how income and recent price growth related to affordability and to group states into broader affordability patterns.

## Key Visuals
![Affordability Ranking by State](images/affordability-ranking-by-state.png)

![Most vs Least Affordable States](images/most-vs-least-affordable-states.png)

![Income vs Price Growth](images/income-vs-price-growth.png)

## Key Findings
The results showed that affordability varied widely across states and that home prices alone did not fully explain those differences. Some states appeared more affordable because income levels were stronger relative to housing values, while others looked less affordable because price growth and housing costs outpaced what median income could support. The clustering analysis also helped separate states into clearer affordability groupings instead of relying on a simple ranking alone.

## Takeaway
This project shows how a broader affordability view can support better decision-making than looking at home prices by themselves. For first-time homebuyers, that means affordability should be evaluated using both income and recent housing trends together. For analysts or policymakers, it shows how combining multiple state-level measures can produce a clearer picture of where affordability pressures appear strongest.
