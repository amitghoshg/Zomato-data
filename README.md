# Zomato Data Analysis

This project involves analyzing Zomato restaurant data to gain insights into various aspects of the restaurant landscape. The analysis covers exploring the dataset, identifying trends, and highlighting key information such as popular restaurant types, online order availability, ratings distribution, cost variations, and identifying top-rated and most-voted restaurants.

## Data

The analysis is performed on the `Zomato-data.csv` dataset. This dataset contains information about restaurants, including their name, online order availability, table booking option, rating, number of votes, approximate cost for two people, and the type of restaurant listed.

## Tools and Libraries Used

The following tools and Python libraries were used for this analysis:

* **Jupyter Notebook:** The analysis was conducted in a Jupyter Notebook environment.
* **pandas:** Used for data loading, manipulation, and analysis.
* **numpy:** Used for numerical operations.
* **seaborn:** Used for data visualization, creating plots like count plots and histograms.
* **matplotlib.pyplot:** Used for plotting and customizing visualizations.

## Analysis Process

The data analysis followed these general steps:

1.  **Data Loading:** The `Zomato-data.csv` file was loaded into a pandas DataFrame.
2.  **Data Exploration:** Initial checks were performed to understand the shape of the dataset, view the head of the DataFrame, and identify any missing values.
3.  **Data Cleaning and Transformation:** The 'rate' column was cleaned by removing the '/5' suffix and converting it to a float data type for numerical analysis. The data types of other columns were also inspected.
4.  **Data Visualization:** Various visualizations were created to explore the data, including:
    * Count plot of different types of restaurants.
    * Count plot showing the availability of online ordering.
    * Histogram visualizing the distribution of restaurant ratings.
    * Count plot showing the distribution of approximate cost for two people.
5.  **Key Findings:** Based on the analysis and visualizations, specific insights were extracted, such as identifying the restaurant with the maximum number of votes, the restaurant with the highest rating, and the most expensive restaurant based on the approximate cost for two people.

## Key Findings

The analysis revealed several interesting points about the Zomato data:

* **Most Voted Restaurant:** Empire Restaurant received the highest number of votes (4884).
* **Top Rated Restaurant:** Onesta has the top rating of 4.6.
* **Most Expensive Restaurant:** Ayda Persian Kitchen was identified as the most expensive with an approximate cost for two people at ₹950.

## Conclusion

The project provides a basic analysis of the Zomato dataset, offering insights into restaurant types, user preferences (based on ratings and votes), and cost considerations. This analysis can serve as a foundation for further, more in-depth exploration or potential predictive modeling.
