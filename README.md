# Ensemble_Learning 

In this repository, various ensemble learning methods is implemented.

Ensemble refers to a number of different learners which are trained on the same dataset with a few nuances to attain a better performance when combined together.

The three import questions in ensemble learning are
- the kind of individual learner to use 
- How should individual learners be trained and
- how should individual learners be combined

we work with two datasets. one is for classisification and the other for regression. 


For our voting classifier(classifiction problem), a bank data gotten from <a href=https://www.kaggle.com/itsmesunil/bank-loan-modelling target='_blank'>here.</a> is used to predict if the customer are eligible for and use a credit card.

The bagging and pasting techniques are also used to build a diverse set of classifiers. A regression model is built using a concrete dataset gotten from <a href=https://www.kaggle.com/maajdl/yeh-concret-data target='_blank'> here</a>

Setting the boostrap argument of the BaggingRegressor to False, performs the pasting while setting the argument to True performs Bagging.

We also worked with adaboost which is amthod which each misclassified training point are given higher relative weights. 

Wealso worked with gradient boosting where each consecutive worked with the residualof the previous model. 

This repo also talked about stacking that answers the question, How should individual models be combined to give the finest output? Stacking allows us train an additional model andcombine the output of individuallearners. this model will be trained on the prediction of the individual learners. This model sometimes called the blender or the meta learner 