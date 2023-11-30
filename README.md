# Movies_EDA_Python
Movies_EDA_python

 EDA serves a crucial purpose in understanding and extracting insights from the movie dataset. 

1.    Data Import and Initial Exploration:   
   -    Library Imports:    Bringing in essential libraries like Pandas, NumPy, Seaborn, and Matplotlib.
   -    Data Loading:    Loading the 'movies.csv' dataset into a DataFrame named `df`.
   -    Initial Exploration:    Understanding the dataset's structure through methods like `head()`, `tail()`, `shape`, and examining missing values using `isnull().sum()`.

2.    Data Cleaning:   
   -    Feature Engineering:    Creating a new 'Year' column by extracting information from the 'released' column.
   -    Handling Missing Values:    Managing missing values in the 'gross' column by converting it to numeric type and then to integers.
   -    Sorting:    Arranging the DataFrame by 'gross' and 'Year' in descending order.

3.    Exploratory Data Analysis (EDA):   
   -    Genre Distribution:    Analyzing the distribution of genres to identify common and rare genres.
   -    Top Contributors:    Identifying top directors, writers, and production countries based on their contributions.
   -    Outlier Detection:    Identifying outliers using boxplots to understand the spread and potential anomalies.
   -    Visualizations:    Utilizing scatter plots and regression plots to visualize relationships between 'budget' and 'gross'.

4.    Data Transformation and Correlation Analysis:   
   -    Numeric Conversion:    Converting specific columns ('budget', 'gross') to numeric data types.
   -    Categorical Transformation:    Transforming categorical data using factorization to prepare for correlation analysis.
   -    Correlation Analysis:    Computing correlations between different variables using various methods and visualizing them through heatmaps.

5.    Company Gross Revenue Analysis:   
   -    Revenue Grouping:    Grouping data by 'company' and 'year' to analyze total gross revenue for companies.
   -    Top Revenue Companies:    Displaying the top 15 companies with the highest total gross revenue.

6.    Conclusion:   
   -    Summary:    Summarizing the overall insights gained from the entire analysis, providing a holistic view of the movie industry dataset.
