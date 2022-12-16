# Minimizing Lending Company Losses By Predicting The Credit Risk Using Machine Learning Model

A good analysis of the borrower's profile is needed in a lending company to minimize the risk of default. Therefore, in this project, a machine learning model will be created with the aim of reducing mistakes in lending money to borrowers in the "bad loan" category by at least 5%.

There are several loan statuses of borrowers such as:
* Fully Paid
* Charged Off
* Current
* Default
* Late (16-30 Days)
* Late (31-120 Days)
* In Grace Period
* Does not meet credit policy. Status : Fully Paid
* Does not meet credit policy. Status : Charged Off
Each of that unique values can be categorized into `good-loan` and `bad-loan`.

Bad-Loan customers are customers that have loan status such as :
* Charged Off
* Default
* Late (16-30 Days)
* Late (31-120 Days)
* Does not meet credit policy. Status : Fully Paid
* Does not meet credit policy. Status : Charged Off

From 466285 data, there are still around 11.6% of borrowers fall into the `bad loan` category. In this project Loan Status will be used as dependent variable.
![image](https://user-images.githubusercontent.com/113236791/208075337-9a2143eb-dbb0-48b6-828f-b256a926f829.png)

Because there are hundreds of data points to train and it was binary classification, I decided to use a simple algorithm such as logistic regression because the training time of the logistic regression algorithm was far less than most complex algorithms. Evaluation of the model can be seen from picture below:

![image](https://user-images.githubusercontent.com/113236791/208075853-0d244d46-ed79-49a5-b6a8-802591205612.png)

![image](https://user-images.githubusercontent.com/113236791/208075898-536e1bf1-4177-4a29-8d5c-8deca3999b58.png)

![image](https://user-images.githubusercontent.com/113236791/208075996-7fbf1cc2-89ad-42a4-90db-00d66db7f4b2.png)

![image](https://user-images.githubusercontent.com/113236791/208076040-06c929a5-9ad1-4cfc-8bf3-3a1a9bef6e96.png)

Simulation Result : Machine Learning model can reduce the number of `bad-loan` approval by 9.68%

![image](https://user-images.githubusercontent.com/113236791/208076575-17dc996c-c43a-47b7-8606-7746df4fe764.png)

Several recommendation for the lending company :
* Using machine learning models, because the model is proven to have good performance to minimize losses (High precision). The model can also be a reference for decision-making by lending company teams.
* Adding a new tenor for the loan period, for example, 48 months. Because from the insights obtained, it can be seen that most borrowers choose to take a tenor of 36 months compared to 60 months. Hopefully adding a new tenor that is between 36 - 60 months will be a good alternative for borrowers.
* The purpose of educational lending appears to be high-risk for the lending company. Educational goals also have the lowest average interest rate compared to other purposes, of course, this is not worth the risk that can be obtained by the company. The company can consider writing off loans for educational purposes, or another alternative is to increase the interest rate by at least the same as the highest interest rate that is available.
