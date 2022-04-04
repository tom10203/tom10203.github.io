## Thomas Franklin
Welcome to my portfolio. Here are a few projects that I have worked on to test my skills and to show what I am capable of. I will continue to post new projects as I go along and to update the ones already on this page. I hope you like what you see!

### [Wine Prediction - K-Nearest Neighbors Algorithm (KNN)](https://github.com/tom10203/Wine-KNN)
This is a KNN algorithm that I wrote down from scratch. I have then used the alogorithm to predict the quality of a wine based on its features.
Here are some of the key steps in vloved in making this project:
- Download the dataset and filter through it to spearte the data I want to use in to a new dataframe.
- Create a function to normalise the data.
- Create a function that finds the distance between datapoints.
- Using a made up wine, create a function that will itterate through the dataset, use the distance function to find the distance between the new wine and the existing data points. 
- Using a given number of nearest neighbors output an estimated quality for the new wine.
- Lastly create one more function that will test the algorithm and ooutput an accuracy value.

### [Weather Forecast - API](https://github.com/tom10203/Weather-API)
This is a block of code that will gather the weather information on a chosen city and output the minimum and maximum temperature of the city at the time of execution.
Some of the steps I took were:
- Use an API to gather information about weather of a chosen city.
- Filter through the information and pick out the min and max temperatures.
- Create a function to convert the temperature from kelvin to celsius.
- Use a while loop so the user can keep using the code until they are finished.

### [Land-Sea-Temperature-Forecast](https://github.com/tom10203/Land-Sea-Temperature-Forecast)
Using a dataset from Kaggle, I have used Scikit Learns Linear Regression model to plot a line of best fit to the data and to predict future temperatures:
- Import the dataset and the libraries needed for manipulating the dataset (Pandas), for the linear regression model (Sk-learn) and for the data-visualisation (mat-plot-lib)
- Divide the dataset in to data and labels
- Plot the data in to a graph
- Use sk-learns linear-regression model to plot a line of best fit
- Fabricate a new set of data and use Sk-learns model to predict the temperature for the future.

### [Daily Crypto-Currency Forecast using Candle-Sticks Graph](https://github.com/tom10203/Crypto-daily-API-and-forecast)
This is a block of code that gathers the daily forecast of BitCoin and outputs a information in to a candlestick graph.
- Use an API to gather the information
- Filter through the the data and pick out the relevant information
- Using a candlestick graph, plot the daily forecast of Bitcoin

### [Loan-Deafault Prediction](https://github.com/tom10203/Loan-Deafault-Prediction-using-SKLearn-Logistic-Regression)
Using SK-Learn, I have used a logistic regression model to predict whether someone will default on their loan. I did this to try and practice my machhine learning and to get more comfortable with SK-Learn.
- Download the dataset and import the relevant libraries
- Wrangle the data
- Reshape the data to be able to feed it to the logistic regression model
- Test the model to see how accurate it is. This can be easily seen through a confusion matrix
- Use the model to predict if a made up customer would defualt on their loan.









