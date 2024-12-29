Instagram Engagement Analysis Project
Overview

This project explores factors influencing user engagement on Instagram, particularly focusing on likes and comments. Using advanced data analytics and machine learning techniques, the analysis aims to identify key predictors and propose actionable recommendations for influencers and marketers.
Objectives

    To identify key variables influencing Instagram engagement metrics (likes and comments).
    To propose and evaluate new variables to improve predictive models.
    To compare engagement strategies for micro (less than 50,000 followers) and macro influencers (more than 50,000 followers).
    To provide actionable recommendations for optimizing engagement strategies.

Dataset Description

The dataset comprises 19,681 Instagram posts with 14 variables capturing content and contextual attributes. The dataset was cleaned, and new variables were engineered for improved analysis. Key columns include:

    LIKES: Number of likes a post received.
    COMMENTS: Number of comments a post received.
    TEXT: Post caption.
    DATE: Date of the post.
    TYPE: Type of post (Photo or Video).
    FOLLOWERS: Number of followers of the user.
    FOLLOWING: Number of accounts the user follows.
    TAGS: Number of hashtags in the post.
    USERS_IN_PHOTO: Number of users tagged in the post.

Engineered Variables:

    Engagement Ratio: Likes + Comments / Followers.
    Text Complexity: Readability score of post captions.
    Sentiment Score: Positivity, neutrality, or negativity of captions.

Methodology

The analysis was structured using the CRISP-DM (Cross-Industry Standard Process for Data Mining) framework:

    Business Understanding: Define goals and critical metrics for analysis.
    Data Understanding: Explore and preprocess the dataset for insights and patterns.
    Data Preparation: Clean data, create dummy variables, and engineer new features.
    Modeling: Run linear regression models for likes and comments.
    Evaluation: Assess model performance using metrics like R-squared and beta coefficients.
    Deployment: Translate findings into actionable strategies for influencers.

Key Findings

    Engagement Ratio is the strongest predictor of both likes and comments.
    Positive sentiment in captions significantly influences comments for micro influencers.
    Weekend posts generally outperform weekday posts in terms of engagement.
    Timing matters: Micro influencers benefit from evening posts, while macro influencers see higher engagement in the afternoon.
    Posts with simpler text receive higher engagement.

Results Visualization

    Visualizations of beta coefficients highlight the most influential predictors for likes and comments.
    Scatter plots and regression lines demonstrate the relationship between key variables and engagement metrics.
    Comparative graphs of micro vs. macro influencer strategies.

Recommendations for Influencers

    Focus on building a high engagement ratio (likes + comments / followers).
    Post during optimal times (Evening for micro influencers, Afternoon for macro influencers).
    Use positive sentiment in captions and maintain simple language for broader appeal.
    Leverage the "weekend effect" to maximize post visibility.

Tools and Technologies

    Python: For data cleaning, feature engineering, and regression modeling.
    Libraries: pandas, numpy, scikit-learn, seaborn, matplotlib, TextBlob.
    Microsoft PowerPoint: For visual presentation of findings.

Deliverables

    Python code for data analysis and visualization.
    A written report detailing the methodology and results.
    A visual presentation summarizing the findings and recommendations.

Acknowledgments

This project was completed as part of the Marketing 568 course at WPI Business School, Fall 2024. Special thanks to Corentin Dugué for the Instagram dataset.
