### Project 6: Finding Donors for CharityML
<p align="center">
    <img width="600" height="300"
     src="https://www.thelifeyoucansave.org/Portals/0/Blog/americancharity.jpg">
</p>

Description:

This repository contains source code, implementing a Logistic
 Regressor model and compares the performance 2 other machine learning
  models (SVM and Decision Tree) in the classification of probable
   donors for a charity event.
   
   The data supplied had a skewed binary class with only 32% of the
    samples being highly probable of being donors. GridSearch and
     subsequent performance validation of the models were performed
      using precision score as the scoring metric to make the model
       give more importance to the target class. A precision score
        of 73% and accuracy score of around 84% was obtained on the
         testing data as opposed to the naive classifier which gave
          a precision score of a meagre 24%.



Technology Used:

* Python 3

Libraries Used:

* numpy
* matplotlib
* seaborn
* sklearn