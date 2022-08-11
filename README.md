# Project_Self_Assessment

## Self Assessment:

Major role in the project group was to work on the technical needs of the project.

I mostly worked on Database Creation and Machine Learning Model.

* Database Creation - We created our DB using Amazon AWS and connected it to Postgres.

* Machine Learning Model - This was the most interesting and tedious part of the project for me.
  Our team selected the dataset from Kaggle and after importing it into the pandas dataframe I started working on cleaning the data which included removing of any null   values and duplicate values as a part data preprocessing followed by Exploratory Data analysis to identify correlation between data features.
  The next step was to split the data into 5 different datasets as we wanted to know how each feature was impacting store sales.
  Then we removed the outliers from the datasets and calculated the Mean Absolute Percentage Error for 3 different Regression Model namely Linear Regression, Random     Forest Regressor.
  Per our analysis the Mean absolute percentage error was least for linear regression so went ahead with linear regression.

We were only able to receive the highest accuracy 75 percent. 
In order to increase the accuracy I also worked on improving the model and made use Logistic Regression but there was no improvement in the accuracy of the model.


##	Team Assessment:


*	Team Communication Policy

In order to ensure the project was completed in a timely, efficient and collaborative manner our team had agreed that we will touch base on our weekly progress every Monday and Wednesday at the start of our collaboration time. Every member is to come to class prepared to update the remainder of the group on their progress for their contribution to the respective weekly deliverable.

If we feel a need for extra collaboration time outside of our lecture hours, Saturdays at 2:00pm will pose as an additional work period.

If any group member feels as through they are unable to complete their work for the week, we ask that they notify the remainder of us by Thursday night so that we can do our best to support them in a timely manner. All rough work/individual submission components are to be completed and uploaded into GitHub by Saturday night so they are ready for a Sunday morning review, push and approval.

* Strengths 

1.) Communication
2.) Dilligent
3.) Attentiuon to detail
4.) Honest and helpful


## Summary 

* Topic - We used stastical regression methods and Python to analyze what impact store area, inventory and customer footfall had on store sales and if linear relationship existed.

* Machine Learning Model - We used Supervised Machine Learning Model mainly regression to determine the MAPE(Mean Absolute Percentage Error) amoong 3 models namely linear regression, random forest regressor and XGBRegressor.
MAE is the mean of the absolute error values (actuals – predictions).

If one wants to ignore the outlier values to a certain degree, MAE is the choice since it reduces the penalty of the outliers significantly with the removal of the square terms.

* Results:

we caluclated MAPE for 5 different through 3 models as mentioned above.
The MAPE was least for Linear Regression ranging from 25 to 28 percent that means the accuracy score ranged fo0rm 72 to 75 percent.












 










