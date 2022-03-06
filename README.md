## Table of content


1. [Installation](https://github.com/unafoca/udacity_ds_project1#Installation)
2. [Project Motivation](https://github.com/unafoca/udacity_ds_project1#Project-Motivation)
3. [File Descriptions](https://github.com/unafoca/udacity_ds_project1#File-Descriptions)
4. [Results](https://github.com/unafoca/udacity_ds_project1#Results)
5. [Licensing, Authors, Acknowledgements](https://github.com/unafoca/udacity_ds_project1#Licensing-Authors-Acknowledgements)

## Installation
In order to run the codes successfully, you'll need to install below packages:<br/>

* pandas (1.1.*)
* numpy (1.18.5)
* json (2.0.9)
* matplotlib (3.2.2)
* seaborn (0.10.1)
* sklearn (0.23.1)
* statsmodels (0.11.1) <br/>

After that the code should run with no issues using Python versions 3.*.

## Project Motivation
For this project, I was interestested in using the simulated data from Starbucks rewards mobile app to investigate:

1. How to generate more promotion impressions?
2. How to make more revenues from viewed promotions?
3. Who would still make purchases without any offer?

The analysis is published in Medium [here](https://cq-w.medium.com/who-would-love-a-cup-of-joe-ca2f1c2549fa).

## File Descriptions
There is one notebook for the codes used to perform the analysis and 3 json files with simulated data:
* portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
* profile.json - demographic data for each customer
* transcript.json - records for transactions, offers received, offers viewed, and offers completed

## Results
The main findings of the code can be found at the post available [here](https://cq-w.medium.com/who-would-love-a-cup-of-joe-ca2f1c2549fa). Below is the summary of the findings:

1. Social media is the most effective promotion channel. Higher income, elder age, longer tenure and non-binary self identified gender all have positive relationship with more impressions.
2. Offers with higher reward rate (reward / required purchase) are much more likely to be completed after seen, so BOGO offers are the most effective ones to attract customers. Other than that, customers with longer tenure and higher income and females have higher possibilities to complete the promotion after seeing it. However, these groups also have higher purchases in general without affected by offers so we cannot quantify the effect just yet.
3. As for next step: we should perform an experiment to see how much more revenue could an offer provide. In addition we should calculate the cost of promotions to make final decisions

## Licensing, Authors, Acknowledgements
Thanks to Starbucks for the data. The analysis won't be possible otherwise. 

Other references:

* [Medium post](https://towardsdatascience.com/dealing-with-list-values-in-pandas-dataframes-a177e534f173) for manipulating list values in Pandas dataframes
* [Sample codes from Udemy course](https://www.udemy.com/course/machinelearning/) for sklearn sample codes for logistic regression
* [Sample codes from post](https://pythonguides.com/scikit-learn-logistic-regression/) for feature importance visualization
