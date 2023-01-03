# You Are Lying!

Nah...just kidding. I over exxagerated, I admitted it. 

As the description says, this is a simple regression project; sorry, it's  __a non-linear regression__ 😝 to determine the relationship between independent variable X and dependent variable y when the data is not distributed linearly, hence the name; __Polynomial Regression__.

We all have known what regression means right? No? It's okay, let me put it here;
<br>
![Regression](https://img.shields.io/badge/-Regression-FFD43B?logoColor=black&style=plastic&logoWidth=20) - Is the statistical method which helps us to estimate or predict the unknown value of one variable from the known value of relation variable. Determining the line of regression means determining the line of best fit. 

That's all in it. Normally, regression which also known as mutiple regression, multivariate regression, ordinary least squares OLS & regression; have few assumptions associated to its model in accordance to the equation 
![Y = mX + b](https://img.shields.io/badge/-Y%20=%20=%20mX&20+%20b-magenta?logoColor=black&style=plastic&logoWidth=20&);
1. __Linearity__: The relationship between X and the mean of Y is linear (where the best fit line is always linear)
2. __Homoscedasticity__:  The variance of residual(or in layman term is "error term") is the same for any value of X. It's literally saying that the variance of the datapoints is roughly the same for all data points.  
3. __Independence__: Observations are independent of each other
4. __Normality__: For any fixed value of X, Y is normally distributed

Let's proceed with the project. Straight to the point; the data is not linearly distributed. There's a few anomalies in the data hence this is no longer a straightforward linear reg problem but a polynomial regression. What's that? Since I'm so nice, I'll write it here 💞.
<br><br>
![Regression](https://img.shields.io/badge/-Polynomial%20Regression-00FFFF?logoColor=black&style=plastic&logoWidth=20&) - Polynomial Regression is a form of linreg in which the relationship between the X and y is not linear but it's the nth degree of polynomial. It's basically saying that the data isn't distributed linearly, instead it's nth degree of polynomial hence the polyreg is used to get the desired output. 

# Project

Apology for the small dataset but you get the gist here right? I'd like to show that linreg is not for all type of data distribution (though it's a go to model 😝) and there's always a solution for that. 

This project will prove the assumption Linearity and Independence (no.1 & no.3) mentioned above. 

## Objective 
The objective of this project is to aim to prove that linreg is not suitable to fit the non-linear nature (polynomial) of data distribution with a low error and accuracy consecutively mitigate the error by producing the best fit line by converting the original features into polynomial features of few degree of polynomial and then modeled it using a linear model. Finally, a Bluffing Detector Reg model is said to be built using the finalized model. Below image is the objective of this project;

![linreg vs polyreg](https://user-images.githubusercontent.com/120354757/210300187-a625d6ec-4834-4912-a1d1-f2b9e4f668c1.png)

## Prob Desc
An HR based Company, which is going to hire a new candidate. The candidate has told his/her previous salary 160K per annum, and the HR have to check whether the candidate is telling the truth or bluffing/lying. Therefore, to identify this, a dataset from the candidate's previous company per levels. From eyeballing the dataset, the pattern of the data is found out to be non-linearly disrtibuted between Position level vs salaries. Next, is to build a Bluffing Detector Regression model is to be used in the future so the HR can hire an honest candidate next time. 

 
## Steps 
The main steps involved in PolyReg are given below;
1. Data Pre-processing
2. Build a LinReg model and fit it to the dataset
3. Build a PolyReg model and fit it to the dataset
4. Visualize the result of LinReg and PolyReg model
5. Prediciting the output
6. Filtering the results

# 

For more real experience, you can open it in Google Colab; 
 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Q7n6ieugI3nuhNSlKphZKF3ccXzEUrxF?usp=sharing)
