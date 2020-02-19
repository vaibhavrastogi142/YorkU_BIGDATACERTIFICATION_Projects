###In this project we aim at unsupervised learning or clustering LA crime data

Abstract
The Los Angeles Police District (LAPD) aims to protect and serve the 4M people of Los Angeles (L.A.).  As part of their commitment to transparency and continual improvement, the City publishes crime and arrest data from 2010 to present (updated weekly) on Kaggle to encourage public dialogue.  Place-based policing is gaining traction as an effective and efficient means to fight and prevent crime, broadening practice from a traditional policing focus on arresting the bad guy.  

In this short study, we look to see what clustering techniques can tell us about crime patterns in L.A..  We are seeking to identify clusters of low, medium, and high risk crime areas and districts in L.A., and to understand the differences between these areas - for example in the prevalence of crime types and victim profiles.  We attempt to use different clustering techniques (dendogram and K-means), scopes (area vs district-level), time periods (2010 to present vs just 2017 which had the highest crime rate) and characteristics (e.g., crime types) for our analysis.

Our K-means clustering analysis was able to identify four clusters where the differences in crime volume by location that were stable over time.  That is, areas of high, medium-high, medium-low, and low crime in L.A..  While our study identifies differences between clusters by crime volume, there were fewer differences than we expected to see between these clusters based on other characteristics (such as crime types and victim and offender socio-economic characteristics) that might help to target police practices and victim services.  This suggest our clusters would need further refinement to become deployable in targeting services.  Our findings nevertheless support the concept of place-based policing - as the most significant differences we identified through our clustering analysis were between locations (by volume).  This is a complex and rich data set, and we view that clustering techniques, with further time to explore different avenues including differences between patterns for crimes vs arrests datasets that surfaced in our exploratory analysis would provide additional insight.   

This file contains the following sections
1. Business Understanding
2. Data Cleaning, Exploration and Preparation
3. Modelling - Clustering
4. Results
