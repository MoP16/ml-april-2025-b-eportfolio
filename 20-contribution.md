## My Individual Contributions: Group Airbnb Project

My contributions to the group project focused on two key areas: setting the initial strategy and performing the foundational data analysis that drove our team's success. Drawing on my business experience, I developed the initial project proposal, framing our work as a value-added service for hosts. This business-oriented approach helped guide the team's technical direction and decision-making from the start.

My primary technical role was leading the **Exploratory Data Analysis (EDA)**. Using R and Power BI, I created the key visualizations that allowed our team to understand the dataset's complexities and directly led to the ideation of our most impactful engineered features.

Below are key examples of the visuals I produced during this phase:

![Price Distribution Analysis](assets/images/010-price%20distribution.png)
*A histogram showing the initial skewed price distribution, which informed our decision to apply a log transformation.*

![Price Variation by Neighbourhood](assets/images/012-price%20distribution%20by%20neigbourhood%20group.png)
*Box plots revealing Manhattan as a distinct, high-cost market, confirming that `neighbourhood_group` was a critical feature.*

![Geospatial Clustering of Listings](assets/images/030-clustering%20k%20means.png)
*K-Means clustering I performed to create new, data-driven geographical zones for our model.*

[![Geospatial Price Distribution](assets/images/013-price%20distirbution%20on%20map.png)](assets/images/013-price%20distirbution%20on%20map.png)
*A geospatial heatmap providing a granular view of price concentrations across NYC.*

[![Correlation Matrix](assets/images/020-correlation%20matrix.png)](assets/images/020-correlation%20matrix.png)
*A correlation matrix revealing weak linear relationships with price, guiding us towards non-linear models.*

---

While the final model implementation was a collaborative effort, my work in data preparation and feature engineering was instrumental to the outcome. It provided the high-quality data needed to progress from a poor-performing baseline Linear Regression model (MAE of **$209**) to our final, highly accurate XGBoost model (MAE of **$32.17**). My analysis was the essential groundwork that enabled the team to build a successful predictive model and achieve our project goals.
