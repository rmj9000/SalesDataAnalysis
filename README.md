### Episode IV: First Data Boot Camp Hackathon - In the beginning...

## Aim of this project

The aim of this project is to familiarise myself with Python and the associated data visualisation tools, in this case, MatPlotLib, Seaborn and Plotly, utilising Numpy and Pandas.

A full analysis would have consisted of possibily more numerous (and logical) visualisations to demonstrate insights into this historical data, which was admittedly incomplete according to the Kaggle site this was downloaded from. For the purposes stated, this was not intended to be a thorough deep anlaysis of the provided sales data. Thise ReadMe is written to take into account some of the actions that would be taken when analysing this data.



## Data-sets Used

The data was provided with historical sales data for 45 stores located in different regions - each store contains a number of departments. The company also runs several promotional markdown events throughout the year. These markdowns precede prominent holidays, the four largest of which are the Super Bowl, Labor Day, Thanksgiving, and Christmas. The weeks including these holidays are weighted five times higher in the evaluation than non-holiday weeks.

Link for the data-set: https://www.kaggle.com/datasets/manjeetsingh/retaildataset/data which contained the following 3 data-sets in comma separated format:
1. Features data set.csv
2. sales data-set.csv
3. stores data-set.csv

Stores contains anonymised information about the 45 stores, indicating the type and size of store.

Features contains additional data related to the store, department, and regional activity for the given dates:

1. Store - the store number
2. Date - the week
3. Temperature - average temperature in the region
4. Fuel_Price - cost of fuel in the region
5. MarkDown1-5 - anonymised data related to promotional markdowns. MarkDown data is only available after Nov 2011, and is not available for all stores all the time. Any missing value is marked with an NA
6. CPI - the consumer price index
7. Unemployment - the unemployment rate
8. IsHoliday - whether the week is a special holiday week

Sales contains historical sales data, which covers to 2010-02-05 to 2012-11-01, with the following fields:

1. Store - the store number
2. Dept - the department number
3. Date - the week
4. Weekly_Sales -  sales for the given department in the given store
5. IsHoliday - whether the week is a special holiday week


## Real World Analysis of Real World Data

The task is to analyse the data and therefore
1. Predict the department-wide sales for each store for the following year
2. Model the effects of markdowns on holiday weeks
3. Provide recommended actions based on the insights drawn, with prioritization placed on largest business impact


## Tools Used

1. Python
2. Numpy
3. Panda
4. Matplotlib
5. Seaborn
6. Plotly


## How To Do This?

Set-up of Jupyter Notebooks to use Python, Pandas, Numpy in the initial stages to check the data types, clean the date and look for duplicates and null values.
Identy useful data and trends to be able to predict future trends and where the business should put more focus. Data visualisations (using matplotlib, seaborn and plotly) will assist in making a wall of numbers look more meaningful to managers and help them gain more knowledge around the factors that drive their business, and aid them in making decisions in future.


## Implementation

Three Jupyter Notebooks were set up. The first to load and look at the data, look for duplicates, null values, clean and add addition columns to aid data visualisation to be done with the resultant out from the first Jupyter Notebook. The 2nd Jupyter Notebook was used for visualisations using matplotlib and seaborn, while the 3rd one was used for interactive visualisations created using plotly.


## Ethics

The data was anonymised so that no individual store, employee or customer could be directly identified.
Bear in mind that this data is from the US where the laws are different from GDPR in the UK & EU, and may not necessarily stand up to the same expected rigour, but the assumption would be that this data was collected in compliance with local laws.


## Challenges

Plotly was not included in the requirements.txt repository that this project template was forked from so was installed using pip install, then pip list to make sure it was an installed package.


## Additional Information / Credits

-The Code Institute LMS systems which contained our lessons on Python, NumPy, Pandas, Data Visualisations and were an invaluable resource to go back over alongside the notes I had made.

-This YouTube Video was used to refresh understand of the use of NumPy:
"Learn NUMPY in 5 minutes - BEST Python Library!" (the video is just under 14 minutes)
https://www.youtube.com/watch?v=xECXZ3tyONo

-Co-Pilot to clean up or correct code using prompts engineering abilities.


## Thanks and Acknowledgements

The staff at Code Institute who were very helpful in their lessons and advice: Emma Lamont, Mark Briscoe, John Rearden & Niel McEwen.

My fellow Data Boot Camp students, of who they are too many to name, for their camaraderie, advice, help and banter.

This funny video about a French tongue twister which helped lighten the mood when I needed a quick break:
https://www.youtube.com/shorts/fQFva6g57Ak

