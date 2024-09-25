<b><h1>Data Analytics for Today:</h1></b>
Enhancing Passenger Satisfaction:  Data Analysis and Modelling Techniques for Skywards International Airlines

I got <b>103,904</b> records of the dataset, which I loaded with pandas, the I proceeded to cleaning of my data by removing Null Value, removing duplicate and the rest.

I continued my analysis by transforming the Text data to Numerical data using Astype.cat.codes() function.

Almost before my descriptive analysis, I used boxplot to determine outliers so as to remove them if any.

<b>My descriptive analysis was done on:</b>
Evaluating the customer satisfaction rate,
Number of Satisfied customers by Gender
Evaluating the relationship between delay and flight distance
Evaluation of passenger rate based on class

Furthermore, to determine the type of predictive model that I will pick, I used Histogram Visualization to check all the features correlation, which 2 out of 28 features are linear correlated.

In addition to my predictive model selection, I advanced to use <b>Heatmap</b> which the correlation matrix report showed 26 out of 28 features were below 0.5 which means they are non-correlated.

These two reports gave me the confidence to pick classification models for this analysis.

<b>Analysis</b><br>
Two models were selected to analyze with and they are Decision tree and Adaboost Predictive Models

Adaboost:
Classification metric, Accuracy metric, and confusion metric were done

Decision Tree:
Classification metric, Accuracy metric, and confusion metric was done

<b>Conclusion on the selected predictive model</b><br>
All the two models metric were brought together and it was noticed that the true positive value for the decision tree classifier is 4938 while Adaboost is 4487 and many more which denoted that Decision tree classifier is better in prediction compared to Adaboost.

Access the application on google colab:  <b>https://colab.research.google.com/drive/1F2X-D0rYjT3C8pM2y4goDSWspi2Pc-QU?usp=sharing#scrollTo=AQq5le6L9POk</b> <br>
Access the code on github: <b>https://github.com/ajayi-abolore/Data-analysis-for-Passenger-Satisfaction</b>

<b>Application used:</b> VScode, Jupyter notebook, google colab  <br>
<b>Libraries used:</b> Pandas, numpy, seaborn, matplotlib, plotly, adaboostclassifier, decisiontreeclassifier, copy.

python
