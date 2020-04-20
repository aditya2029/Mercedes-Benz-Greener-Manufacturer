# Mercedes-Benz-Greener-Manufacturer
### Business Problem:

Since the first automobile, the Benz Patent Motor Car in 1886, Mercedes-Benz has stood for important automotive innovations. These include, for example, the passenger safety cell with crumple zone, the airbag, and intelligent assistance systems. Mercedes-Benz applies for nearly 2000 patents per year, making the brand the European leader among premium carmakers. Daimler's Mercedes-Benz cars are leaders in the premium car industry. With a huge selection of features and options, customers can choose the customized Mercedes-Benz of their dreams.
To ensure the safety and reliability of each and every unique car configuration before they hit the road, Daimler's engineers have developed a robust testing system. But, optimizing the speed of their testing system for so many possible feature combinations is complex and time-consuming without a powerful algorithmic approach. As one of the world's biggest manufacturers of premium cars, safety and efficiency are paramount on Daimler's production lines.
In this competition, Daimler is challenging Kagglers to tackle the curse of dimensionality and reduce the time that cars spend on the test bench. Competitors will work with a dataset representing different permutations of Mercedes-Benz car features to predict the time it takes to pass testing. Winning algorithms will contribute to speedier testing, resulting in lower carbon dioxide emissions without reducing Daimler's standards.

### Problem Statement:
To predict the target variable ‘y’ lie time in seconds that the car needs to pass the testing.

### Real World / Business Objectives and Constraints:
1.	Predict time in seconds with a high value of R² (Coefficient of determination).
2.	No strict latency constraints.

### The performance metric used here is:
R2 (Coefficient of determination): It is the proportion of the variance in the dependent variable that is predictable from the independent variables.

### First Cut Approach:

As 'y' is a continuous variable, so it is a regression problem. Initially, I can think of the Linear Regression approach as my benchmark model because it is the simplest regression algorithm we have. So, my initial approach is as follow:

1.	Importing essential libraries
2.	Perform EDA for understanding dataset and feature analysis
3.	We have to perform dimensionality reduction techniques as Mercedes already told us on Kaggle that we have to deal with the curse of dimensionality. We can get a better understanding by analyzing the data.
4.	Standardization and featurization of train data
5.	Preparing test data
6.	Train the baseline model
7.	Evaluate the result based on R2 Score
8.	Based on the result of the baseline model, try more complex models for further improvement.

### Conclusion:
The best score we got from stacking regressor 0.55227.
According to the Kaggle Private Leader board, with a score of 0.55227, standing will be 156th position – 190th position which is under 5% of total participants.


