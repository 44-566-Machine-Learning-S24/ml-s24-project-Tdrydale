# Analysis

The models I used for this project included Linear Regression, Decision Trees, SVM, K-means clustering, and Random Forests. The model that performed the best was the Decision Tree with a 0.89, the test set got a 0.94 so it was probably underfitting, most of the data was easy for it to get correct, giving it more values would bring it closer to the training average. The reason I think that the Decision tree did so well was because of how I split the prices up into 3 groups, it made it really easy for the decision tree to be able to guess what price range the buildings could sell for. 

SVM got around a 0.73, it didn't do that great because it put most of it's guesses in the category that had the most right answers. Linear Regression got a 0.49, it acted pretty weird when I added the polynomial features, towards the end of the line the price fell back down, there was a few outliers that were big sizes of buildings but sold/listed for low amounts. I imagine these data points are building that aren't in great condition, like old warehouses, adding more data with bigger buildings might change this result. Random forests did pretty good with a 0.89, but it looked like it overfit on the dataset because the test got 0.8. 

One improvement i would like to make with this data set is instead of focusing on a certain state i want to narrow down and focus on a city. I think this would have better results, as selling a building in the middle of nowhere will not go for as much as a building that is in the middle of a huge city. There is a feature that tells the city sold in this dataset, but i imagine that i would need to grab more data for this dataset or find a new dataset that is already focused on a big city. Another change i would like to make is to split the price category i made up more, looking back i think that 3 was a pretty small number of categories to split into considering these houses are ranging from prices of 100,000 to 1,000,000. It would be interesting to see if it still preforms as well or if it would start guessing more of the values incorrectly.

Files:
* [Linear Regression](linear_regression.ipynb)
* [Classification](classification.ipynb)
* [Clustering and Random Forest](clustering_random_forest.ipynb)
