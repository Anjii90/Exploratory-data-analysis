# Exploratory-data-analysis
# Airbnb NYC Analysis

## About the Project

This project aims to explore and analyze a dataset containing approximately 49,000 Airbnb listings in New York City. The goal is to uncover key insights that can enhance platform performance and improve the user experience. The dataset consists of 16 columns, including categorical and numerical data such as listing details, host information, location coordinates, room types, pricing, and review statistics.

## Dataset Overview

- **Number of records:** ~49,000
- **Columns:**
  - `id`: Unique identifier for each listing
  - `name`: Name of the listing
  - `host_id`: Unique identifier for each host
  - `host_name`: Name of the host
  - `neighbourhood_group`: Borough where the listing is located
  - `neighbourhood`: Specific neighborhood of the listing
  - `latitude` & `longitude`: Geographical coordinates of the listing
  - `room_type`: Type of listing (Entire home/apt, Private room, Shared room)
  - `price`: Price per night
  - `minimum_nights`: Minimum required nights per stay
  - `number_of_reviews`: Number of reviews for the listing
  - `last_review`: Date of the last review
  - `reviews_per_month`: Average reviews per month
  - `calculated_host_listings_count`: Number of listings per host
  - `availability_365`: Number of available days in a year

## Data Preprocessing

1. **Handling Missing Values:**
   - Dropped rows with missing values in `name` and `host_name`.
   - Filled missing values in `last_review` with "No Review".
   - Filled missing values in `reviews_per_month` with `0`.
   - Converted `last_review` to a datetime format.

2. **Descriptive Statistics:**
   - Calculated summary statistics such as mean, median, variance, and standard deviation for numerical columns.

## Key Insights

### Neighbourhood Group Popularity

- **Manhattan (21,643 listings) and Brooklyn (20,089 listings) are the most popular boroughs.**

### Room Type Preferences

- **Entire home/apartment listings dominate (25,393), followed by private rooms (22,306).**

### Price Distribution

- **The median listing price is $106.**
- **Price range varies from $0 to $10,000, with 75% of listings priced at $175 or lower.**

### Correlations

#### Price vs. Room Type

- **Entire homes/apartments have the highest average price ($211.80).**
- **Private rooms are priced lower at an average of $89.79.**
- **Shared rooms are the most affordable, averaging $70.07.**




