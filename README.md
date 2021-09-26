# Surfs up challenge

![image](https://user-images.githubusercontent.com/86340630/134797652-4a34e08e-0a25-4e66-a9aa-67bd7ce293d5.png)


Surfs Up
Project Summary and Background
W. Avy likes your analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

What You're Creating
This new assignment consists of two technical analysis deliverables and a written report. You will submit the following:

Deliverable 1: Determine the Summary Statistics for June
Deliverable 2: Determine the Summary Statistics for December
Deliverable 3: A written report for the statistical analysis README.md.
Resources and Before Start Notes:
Data Source: SurfsUp_Challenge_starter_code.ipynb named later as SurfsUp_Challenge.ipynb
Data File: hawaii.sqlite
Software: Matplotli 3.2.2, Python 3.9, Visual Studio Code 1.50.0, Anaconda 4.8.5, Jupyter Notebook 6.1.4, Pandas, Numpy, Sqlalchemy.

# Deliverable 1: Determine the Summary Statistics for June
Using Python, Pandas functions and methods, and SQLAlchemy, you’ll filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June. You’ll then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.

Deliverable Requirements:
You will earn a perfect score for Deliverable 1 by completing all requirements below:

A working query is written to retrieve the June temperatures from the date column of the Measurement table.
The temperatures are added to a list.
The list of temperatures is converted to a Pandas DataFrame.
Summary statistics are generated for the DataFrame.
Results with detail analysis:
A working query is written to retrieve the June temperatures from the date column of the Measurement table.

![image](https://user-images.githubusercontent.com/86340630/134799217-50893b84-4d23-45b6-9e4b-3bb1595e481c.png)

The temperatures are added to a list.

![image](https://user-images.githubusercontent.com/86340630/134799337-f2bb7ee1-4e7b-4c11-a3a3-824a4b6d8732.png)

The list of temperatures is converted to a Pandas DataFrame.

![image](https://user-images.githubusercontent.com/86340630/134799379-c6fb9766-8480-4484-b550-09c4ed9f0930.png)

Summary statistics are generated for the DataFrame.

![image](https://user-images.githubusercontent.com/86340630/134799401-dd0abb8a-0ea3-4339-90d4-93790eb0b088.png)

# Deliverable 2: Determine the Summary Statistics for December.
Using Python, Pandas functions and methods, and SQLAlchemy, you’ll filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of December. You’ll then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.

Deliverable Requirements:
You will earn a perfect score for Deliverable 2 by completing all requirements below:

A working query is written to retrieve the December temperatures from the date column of the Measurement table.
The temperatures are added to a list.
The list of temperatures is converted to a Pandas DataFrame.
Summary statistics are generated for the DataFrame
Results with detail analysis:
A working query is written to retrieve the December temperatures from the date column of the Measurement table.

![image](https://user-images.githubusercontent.com/86340630/134799439-c2f878ff-91ea-4e5c-9d71-88cbc8f31aa5.png)

The temperatures are added to a list.

![image](https://user-images.githubusercontent.com/86340630/134799531-d7e084f4-5498-4e88-9561-1e85b7b04ba8.png)

The list of temperatures is converted to a Pandas DataFrame.

![image](https://user-images.githubusercontent.com/86340630/134799562-f696afe7-e76d-4019-bc0d-3fdae7931eb5.png)

Summary statistics are generated for the DataFrame.

![image](https://user-images.githubusercontent.com/86340630/134799609-96732f14-cc72-49bc-85dd-53b94b2b1b2e.png)

# Deliverable 3: A written report for the statistical analysis
For this part of the Challenge, write a report that describes the key differences in weather between June and December and two recommendations for further analysis.

The analysis should contain the following:
Overview of the analysis: Using Python, Pandas functions and methods, and SQLAlchemy, we’ll filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June. We'll then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics. Once our dataframe is created we are able to get our summary statistics by using the df.describe() code and method.
Below our Analysis that what we found:

Results: Data Provided gave us a visibility that on months of June and December, our location had a total Temps of:
June Temps - Analysis and Result

Count of 1700
Mean of 74.94
Std of 3.26
Min of 64.00
25% of 73.00
50% of 75.00
75% of 77.00
Max of 85.00
June Temps - Report

![image](https://user-images.githubusercontent.com/86340630/134799650-4d61ab36-c9b0-4f4b-9b93-dce314bdd5d9.png)

December Temps - Analysis and Result

Count of 1517
Mean of 71.04
Std of 3.75
Min of 56.00
25% of 69.00
50% of 71.00
75% of 74.00
Max of 83.00
December Temps - Report

![image](https://user-images.githubusercontent.com/86340630/134799679-e3982de4-392b-4d54-8fb2-808c2555d390.png)

Summary: Based on our Data Analysis, Data Provided, we can state as a high-level summary of results that Standard deviation is 3.25 in June and 3.75 in December, making a 0.5 difference between both seasons.

In addition, current data provide attributes such precipitation and others, with two queries that our analysis pursue, performing weather data for June and December that helps results to decide how we would like to build the shop and what areas would make this location attractive to visitors to stop by and have a successful business.










