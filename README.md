# PyBer_Analysis

## Project Overview
The project's scope includes the following list of steps and deliverables:

- Import your data into a Pandas DataFrame.
- Merge your DataFrames.
- Create a bubble chart that showcases the average fare versus the total number of rides with bubble size based on the total number of drivers for each city type, including urban, suburban, and rural.
- Determine the mean, median, and mode for the following:
	- The total number of rides for each city type.
	- The average fares for each city type.
	- The total number of drivers for each city type.
- Create box-and-whisker plots that visualize each of the following to determine if there are any outliers:
	- The number of rides for each city type.
	- The fares for each city type.
	- The number of drivers for each city type.
- Create a pie chart that visualizes each of the following data for each city type:
	- The percent of total fares.
	- The percent of total rides.
	- The percent of total drivers.

## Resources
- **Data Sources**: 
- **Software**: Python 3.7.6, Anaconda 4.9.2, Git Bash 2.29.2
- **Tools**: Jupyter Notebook, Pandas, Matplotlib 3.3.2 

## Challenge Overview
V. Isualize has given you and Omar a brand-new assignment. Using your Python skills and knowledge of Pandas, you’ll create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type. Finally, you’ll submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

What You're Creating
This new assignment consists of two technical analysis deliverables and a written report to present your results. You will submit the following:

Deliverable 1: A ride-sharing summary DataFrame by city type
- The total number of rides for each city type is retrieved.
- The total number of drivers for each city type is retrieved.
- ​The sum of the fares for each city type is retrieved.
- ​The average fare per ride for each city type is calculated.
- The average fare per driver for each city type is calculated.
- A PyBer summary DataFrame is created.
- The PyBer summary DataFrame is formatted as shown in the example.

Deliverable 2: A multiple-line chart of total fares for each city type
- A DataFrame was created using the groupby() function on the "type" and "date" columns, and the sum() method is applied on the "fare" column to show the total fare amount for each date and time.
- A DataFrame was created using the pivot() function where the index is the "date," the columns are the city "type," and the values are the "fare."
- A DataFrame was created using the loc method on the date range: 2019-01-01 through 2019-04-29.
- A DataFrame was created using the resample() function in weekly bins and shows the sum of the fares for each week.
- An annotated chart showing the total fares by city type is created and saved to the "analysis" folder.

## Challenge Deliverables
What You're Creating
This new assignment consists of two technical analysis deliverables and a written report to present your results. You will submit the following:

### Deliverable 1: A ride-sharing summary DataFrame by city type

### Deliverable 2: A multiple-line chart of total fares for each city type

## Challenge Results
Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.

There is a description of the differences in ride-sharing data among the different city types. Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type. 

## Challenge Summary
Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.