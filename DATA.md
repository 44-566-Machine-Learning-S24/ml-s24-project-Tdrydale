# Data

Because of the large quantity of data I had to work with, I cut down a lot of the data to work with a more manageable amount. I got rid of any data that had missing values, limited the price to 2 million, limited the number of beds/baths to cut out some outliers, and most importantly only focused on data in a specific state. Working with one state was one of my most important decisions at this stage of data exploration, prices can fluctuate drastically when looking at selling prices between states, a house that sells in Iowa can be a lot cheaper than a house selling in Florida.

When choosing my state to work with and what data to focus on I used data that was most correlated with each other. I split the prices into different categories because it would be almost impossible to guess the exact selling price of the building. I split the retail price into thirds, low, average, and high prices, to determine the splitting points I tried to split it as evenly as possible. 

Files:
* [Initial exploration](initial_exploration.ipynb)
