## British Airways Airline Review Analysis

### Project Background
British Airways, one of the leading global airlines, has been serving passengers since 1974. With a business model focused on both leisure and business travelers, the airline provides a range of services across multiple classes, including Economy, Business, and First Class. The company focuses on enhancing customer satisfaction by regularly analyzing key business metrics such as overall ratings, cabin staff service, and in-flight entertainment quality. This project evaluates customer feedback spanning from **March 2016 to October 2023**, with the aim of identifying trends in satisfaction across regions, aircraft, and traveler types to offer actionable recommendations for improving customer experience.

### Insights and recommendations are provided on the following key areas:
- **Overall Customer Rating Trends**: Analyzing fluctuations in customer satisfaction over time.
- **Ratings by Aircraft Type**: Identifying the best and worst-performing aircraft in terms of customer satisfaction.
- **Geographical Trends in Ratings**: Understanding regional patterns in customer reviews.
- **Traveler and Seat Type Preferences**: Exploring how different traveler types and seating options affect overall ratings.

### Data Structure & Initial Checks
The dataset was primarily structured around customer reviews across multiple factors, including overall rating, cabin staff service, entertainment, and food. The Tableau dashboard contains various filters such as month, aircraft type, and traveler type to enable a deep dive into specific areas of interest. 

Key tables used in the analysis:
- **Customer Reviews**: Consisting of over 10,000 review entries.
- **Aircraft Types**: Detailed information on aircraft models, including Boeing and Airbus variants.
- **Geographical Data**: Regional breakdowns based on review origin.

---

## Executive Summary
### Overview of Findings
This analysis reveals the following overarching trends:
1. **Customer satisfaction has generally declined post-2020**, likely due to the pandemic's impact on airline operations.
2. **The Boeing 747-400 performed the best** in terms of customer ratings, averaging **4.7**, while the **Boeing 777-200** had the lowest satisfaction rate despite having the most reviews.
3. **Entertainment services** received the lowest average rating (1.4), indicating an area of focus for improvement.

View Tableau Dashboard [here](https://public.tableau.com/views/BritishAirlineAirwaysReview/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).

---

## Insights Deep Dive

![Airline Analysis](https://github.com/AngelicaDolor/airline-review-analysis/blob/main/airline-analysis.png)

### Category 1: **Overall Customer Rating Trends**
- **Insight 1**: Average overall customer ratings showed a consistent decline after 2020, dropping from **4.8 to 4.2**.
  - **Supporting Analysis**: The ratings were stable from 2016 to 2019 but saw a drop due to post-pandemic service adjustments.
- **Insight 2**: The highest ratings were observed during the years **2017 to 2019**, peaking in early 2018 at **5.0**.
- **Insight 3**: Seasonal dips are noticeable during the winter months, especially around **December**.
- **Insight 4**: Peak satisfaction levels are noted during **late spring and summer**, coinciding with high travel periods.

### Category 2: **Ratings by Aircraft Type**
- **Insight 1**: **Boeing 747-400** received the highest ratings (**4.7**), indicating customer preference for this model.
- **Insight 2**: The **Boeing 777-200**, despite having the most reviews, garnered the lowest average rating (**3.6**), suggesting a need for service improvements.
- **Insight 3**: Airbus models, such as the **A320** and **A380**, maintained a steady rating of around **4.0**, reflecting stable customer satisfaction.
- **Insight 4**: The **Boeing 747 series**, in general, outperformed other models in customer satisfaction across different metrics.

### Category 3: **Geographical Trends in Ratings**
- **Insight 1**: The highest customer satisfaction ratings were recorded in **Western Europe**, where the average rating reached **4.5**.
- **Insight 2**: Regions such as **South America** and **Africa** saw lower average ratings (around **3.0-3.5**).
- **Insight 3**: The **UK** and **US** remained relatively stable with an average rating around **4.2**.
- **Insight 4**: **Seasonal travel patterns** affected ratings in certain regions, with **Europe** showing a dip during winter months.

### Category 4: **Traveler and Seat Type Preferences**
- **Insight 1**: **Business class travelers** rated their experience higher on average (**4.5**) compared to **economy class** (**3.8**).
- **Insight 2**: **Couple leisure travelers** gave higher ratings compared to family or business travelers.
- **Insight 3**: **Premium Economy** passengers provided better ratings than **Economy**, with a **0.5-point** difference on average.
- **Insight 4**: **First-class passengers** provided consistently higher ratings across all categories, especially in cabin staff service.


---

## Recommendations:
Based on the insights and findings above, we would recommend the **Customer Experience Team** at British Airways to consider the following:

1. **Focus on upgrading entertainment options**, as the current average rating of **1.4** suggests significant dissatisfaction in this area.
2. **Address service issues on Boeing 777-200 flights**, which have the most reviews but a lower satisfaction score.
3. **Invest in seat comfort improvements**, especially in **Economy** and **Premium Economy** to match or exceed ratings seen in **Business** and **First Class**.
4. **Maintain the performance of the Boeing 747-400** fleet, which has consistently high customer satisfaction.
5. **Leverage insights from traveler type preferences**, such as improving services targeted at family travelers who tend to rate their experience lower than couples or business travelers.

---

## Assumptions and Caveats:
- **Assumption 1**: Some missing geographical data was inferred based on the flight origin and destination.
- **Assumption 2**: The dataset lacked data for **December 2021**, so trends for that month were inferred based on **December 2020** and surrounding months.
- **Assumption 3**: Outliers in overall ratings below **1.0** were assumed to be data entry errors and were excluded from the analysis.
