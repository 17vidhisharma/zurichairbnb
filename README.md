🏙 Zurich Airbnb Data Analysis

A pricing, segmentation, and behavioural analysis of Airbnb listings in Zurich.


🌐 Overview

This project explores Airbnb listings in Zurich using data cleaning, exploratory analysis, regression modelling, classification, NLP, and clustering.
The objective was to understand:

• what drives listing prices
• how hosts behave
• which neighbourhoods attract higher performance
• how guest engagement patterns influence outcomes

This project was completed as part of my Data Mining coursework and became one of my most in-depth applied analytics pieces of the semester.

🔍 Key Questions

• Which features most strongly influence listing price
• How neighbourhoods differ in supply, demand, and pricing
• Whether host characteristics affect listing success
• Which textual patterns appear in listing descriptions
• Whether listings can be segmented into meaningful clusters

📊 Main Findings
1. Drivers of Pricing

Regression models (linear, regularised, tree based) identified strong relationships with:
• neighbourhood group
• number of reviews
• room type
• sentiment score of descriptions
• minimum nights

The best model achieved R² of approximately 0.7 after feature engineering and tuning.

2. Host Behaviour Classification

A classification model predicted host response behaviour using features such as:
• review score metrics
• availability
• description sentiment
• host tenure

The best model reached 78 percent accuracy.

3. Clustering and Segmentation

Unsupervised clustering revealed distinct listing groups:
• budget friendly high density rooms
• premium private spaces with strong ratings
• niche listings with high variability in amenities

4. Neighbourhood Trends

Certain areas consistently showed higher pricing and lower volatility.
The analysis also highlighted clusters of low review density, signalling either new listings or weaker performance.

🧪 Methods and Techniques

• Data Cleaning
• EDA
• Regression Modelling
• Classification Modelling
• NLP and Sentiment Analysis
• Clustering (KMeans and hierarchical)
• Feature Engineering
• Visualisation
