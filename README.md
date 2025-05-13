Project Title: Enhancing Food Delivery Services with Sentiment Analysis and Predictive Analytics (Zomato Dataset)
 Project Objective :--
The main goal of this project was to analyze customer reviews and delivery data from Zomato to:
Understand factors influencing customer satisfaction.
Perform sentiment analysis on text reviews.
Build predictive models to forecast delivery time and rating patterns.
Derive insights to help improve food delivery services using data.

Tools & Libraries Used :--
Python
Pandas, NumPy – Data cleaning and transformation
Matplotlib, Seaborn – Data visualization
TextBlob, VADER (NLTK) – Sentiment analysis
Scikit-learn – Machine learning models (regression & classification)

Steps and Methodology :--
1. Data Cleaning & Preprocessing
Removed null values and handled inconsistent formatting.
Converted review timestamps and delivery durations into usable numeric features.
Created new features: Delivery_Duration, Sentiment_Score, Review_Length.
2. Exploratory Data Analysis (EDA)
Analyzed delivery time trends by city, order type, and peak hours.
Identified the distribution of customer ratings and review lengths.
Correlated variables like vehicle condition, weather, and traffic with delivery time.
3. Sentiment Analysis
Used TextBlob and VADER to calculate sentiment polarity and classify reviews as positive, neutral, or negative.
Found that higher sentiment scores were associated with better ratings and faster delivery times.
Identified keywords in negative reviews (e.g., "late", "cold", "unprofessional") and in positive reviews (e.g., "on-time", "hot food", "friendly").
4. Predictive ModelingApplied Linear Regression and Random Forest Regressor to predict delivery time.
Used Logistic Regression to classify sentiment-based satisfaction.
Key features contributing to delay predictions: Traffic_Density, Vehicle_Condition, Order_Type, and Weather_Conditions.

Key Results :--
Sentiment analysis accuracy: ~85% using VADER
Regression model R² score: ~0.72 (indicating good fit for delivery time prediction)
Top delay contributors: High traffic, bad weather, poor vehicle condition
Insight: Deliveries with positive sentiment reviews had ~15–20% faster delivery times on average

Business Insights & Recommendations :--
Optimize Delivery During Peak Hours: Higher delays and lower sentiment observed in evening slots.
Invest in Vehicle Maintenance: Vehicles rated lower in condition correlated with longer delivery times.
Customer Feedback Loop: Negative keywords like "cold food" or "late delivery" can be tracked in real-time to alert operations.
Review Sentiment Dashboard: Visualizations can help restaurant managers spot dissatisfaction trends and resolve issues proactively.



