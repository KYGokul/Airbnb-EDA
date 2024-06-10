# Airbnb NYC Listings EDA Project

## Overview

This project involves an exploratory data analysis (EDA) of the Airbnb NYC listings dataset. The dataset contains approximately 49,000 rows and 16 columns, representing a mix of categorical and numeric data. The aim is to understand the data, perform necessary preprocessing, visualize relationships between variables, and derive insights that can help in achieving business objectives.

## Dataset Description

The dataset consists of the following columns:

- **id**: Unique ID for each listing
- **name**: Name of the listing
- **host_id**: Unique ID for each host
- **host_name**: Name of the host
- **neighbourhood_group**: Location (borough)
- **neighbourhood**: Specific area within the borough
- **latitude**: Latitude coordinate
- **longitude**: Longitude coordinate
- **room_type**: Type of listing (Entire home/apt, Private room, Shared room)
- **price**: Price per night
- **minimum_nights**: Minimum number of nights required for booking
- **number_of_reviews**: Total number of reviews
- **last_review**: Date of the last review
- **reviews_per_month**: Average number of reviews per month
- **calculated_host_listing_count**: Total number of listings by the host
- **availability_365**: Number of days the listing is available per year

## Project Steps

1. **Data Loading and Understanding**:
   - Loaded the dataset and created a copy (new_df) for manipulation.
   - Conducted basic EDA to understand the structure and summary statistics of the data.

2. **Data Cleaning**:
   - Dropped rows with null values in specific columns to improve data completeness and accuracy.
   - Excluded rows where the price column is 0, as zero price is unrealistic for any business.

3. **Data Visualization and Analysis**:
   - Created various charts and visualizations to explore relationships between variables.
   - Performed storytelling through data visualization to highlight key insights.

4. **Solution to Business Objectives**:
   - Derived insights and provided solutions to address business objectives based on the analysis.

5. **Conclusion**:
   - Summarized key findings and their implications for the Airbnb business.

## Acknowledgements

- The dataset is given in same repository.
- Thanks to the open-source community for tools and libraries used in this project.
