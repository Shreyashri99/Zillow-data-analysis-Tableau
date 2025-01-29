# PropertyNest: Cracking Boston’s Housing Code
Overview
PropertyNest is a data-driven housing search optimization project aimed at helping users find suitable and affordable accommodations in Boston. Using Zillow rental data, we analyze housing trends, optimize property recommendations, and provide an interactive dashboard for streamlined searches based on location, budget, and living preferences.

# Problem Statement
Finding affordable housing near key landmarks is challenging due to:
Fragmented and inefficient search methods.
Lack of centralized insights on pricing, availability, and legitimacy.
Difficulty in aligning available listings with user preferences.

# Objective
The goal is to optimize housing recommendations by:

Analyzing demand patterns and pricing trends.
Developing an interactive dashboard for efficient searches.
Ensuring affordability, proximity to key locations, and suitability based on user preferences.
Data Collection & Preprocessing
The dataset comprises ~18,000+ Zillow listings with attributes covering price, location, property type, and availability.

Steps Involved:
Data Collection & Integration
Scraped Zillow data and converted JSON to CSV format.
Merged multiple datasets for comprehensive analysis.

# Data Cleaning & Transformation
Handled missing values (e.g., area, bedrooms, bathrooms).
Removed redundant and inconsistent data.
Mapped ZIP codes to neighborhoods in Boston, Cambridge, and Brookline.
Created a “Score” metric based on location proximity and listing attributes.

# Exploratory Data Analysis (EDA)

Correlation analysis between street name, address, and pricing.
Distance calculations from key landmarks.
Identified key pricing trends across different neighborhoods.

# User Story
Meet Jacob, a student at Northeastern University looking for housing:

Where should I stay? → Neighborhood & proximity analysis.
Is the rent fair? → Zestimate price validation.
Can I stay with friends? → Bedrooms & bathrooms analysis.
Are listings legit? → Zillow-owned & showcase listing validation.

# Results & Insights
Key findings using Tableau dashboards:
Seaport District had the highest average housing score.
Brighton had the lowest median rent (~$1100).
Fenway/Kenmore, Roxbury, Chinatown & South Boston were within a 2-mile radius from NEU.
Predictive model developed to replace Zestimate for rent estimation.
