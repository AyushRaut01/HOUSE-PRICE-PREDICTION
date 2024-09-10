# House Price Prediction

This repository contains a project for predicting house prices in King County, Washington (including Seattle), based on homes sold between May 2014 and May 2015. The analysis involves data cleansing, visualization, and exploration of the relationships between house features and prices using Python libraries such as Pandas, NumPy, Seaborn, and Matplotlib.

## Dataset

The dataset includes various attributes like price, number of bedrooms and bathrooms, square footage, location (longitude and latitude), and more. It provides a comprehensive overview of housing features to help analyze price trends in King County.

### Dataset Attributes:
- Price
- Number of bedrooms
- Number of bathrooms
- Square footage (living area and lot)
- Year built
- Floors
- Waterfront property status
- Location (longitude, latitude)

## Steps

### 1. **Data Cleansing and Exploration**
   - Loaded the dataset using Pandas and performed initial inspection using `df.head()`, `df.info()`, and `df.describe()` to understand the structure and key statistics.
   - Checked for missing values in the dataset and reviewed basic descriptive statistics.
   - Sorted the data by price to identify top and bottom 10 most expensive properties.

### 2. **Data Visualization**
   - Used Seaborn and Matplotlib to explore relationships between variables:
     - **House Price Distribution**: Visualized price distribution using a histogram.
     - **Living Space Distribution**: Plotted the distribution of square footage.
     - **Bedrooms and Bathrooms**: Count plots for bedrooms and bathrooms.
     - **Year Built**: Distribution of the year homes were built.
     - **Floors**: Count of houses with different numbers of floors.
     - **Price vs Living Space**: Scatter plot showing the relationship between price and square footage.
     - **Waterfront Properties**: Box plot to show how waterfront properties affect pricing.
     - **Location (Longitude & Latitude)**: Scatter plot mapping homes with price as a hue to visualize geographical price distribution.

### 3. **Correlation Analysis**
   - Calculated the correlation between key features to understand their relationships.
   - Plotted a heatmap to visualize the correlation matrix, which highlights the strength of relationships between variables like square footage and price.

## Libraries Used
- **Pandas**: For data loading and manipulation.
- **NumPy**: For numerical operations.
- **Seaborn**: For advanced data visualization.
- **Matplotlib**: For basic plotting.
- **Warnings**: To suppress unnecessary warnings during analysis.

## Future Work
- Build a predictive model using the cleaned and visualized data.
- Implement machine learning techniques to predict house prices based on the given features.
