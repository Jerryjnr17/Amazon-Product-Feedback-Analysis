Amazon Product Feedback & Sentiment Analysis
Overview

This project analyzes Amazon product reviews to uncover the drivers of customer sentiment and engagement. The analysis combines rating distributions, textual sentiment, and review engagement metrics to generate insights that support product improvement and marketing strategies.

Objective

Understand customer sentiment across products, brands, and categories

Identify factors influencing review engagement and helpfulness

Extract recurring themes from positive and negative reviews

Provide actionable recommendations for product development and marketing

Dataset

Total Reviews: ~3,077

Total Features: 13

Key fields include review text, rating (1–5), recommendation flag, helpfulness votes, brand, category, and review date.

Data Cleaning & Preprocessing

Standardized column names using snake_case formatting

Parsed review date fields into datetime format

Handled missing values:

Imputed missing recommendation flags as “Unknown”

Dropped records with missing review text

Engineered new features:

Review length (word count)

Sentiment polarity score (–1 to +1) using a lexicon-based approach

Helpfulness ratio (helpful votes normalized by review length)

Exploratory Data Analysis
Ratings & Recommendations

Approximately 70% of reviews have 4–5 star ratings

1–2 star ratings represent about 15% of reviews

High ratings strongly align with positive recommendation flags, though some high-rated reviews did not explicitly recommend the product

Brand & Category Sentiment

Certain brands exhibit consistently high sentiment scores (>0.6)

Other brands show lower average sentiment with frequent low-star reviews

Categories such as Electronics display higher sentiment variability compared to more uniform categories like Books

Textual Insights

Positive reviews commonly include terms such as “quality,” “easy,” and “recommend”

Negative reviews frequently reference “defective,” “return,” and “battery”

Longer reviews tend to receive significantly more helpful votes than shorter reviews

Data Visualization

Bar charts for rating counts and recommendation rates

Heatmaps showing average sentiment by brand and category

Word clouds contrasting positive and negative reviews

Scatter plots of review length versus helpful votes

Box plots of helpfulness ratio across rating levels

Key Insights

While most reviews are positive, negative reviews provide deeper insights into product pain points

Longer and more detailed reviews generate higher engagement and perceived usefulness

Certain brands and categories consistently outperform others in sentiment scores

Recommendations

Prioritize fixes for frequently mentioned product defects

Encourage structured reviews highlighting pros and cons

Align marketing messages with features driving high customer sentiment

Deliverables

Fully documented Jupyter Notebook with all code and outputs

Clear visualizations supporting key findings

Actionable insights and business-focused recommendations
