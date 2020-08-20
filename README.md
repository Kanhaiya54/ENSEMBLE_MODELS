# ENSEMBLE_MODELS
Performed Ensemble models, Bagging, Boosting, Stacking of the iris dataset

Overview:
Bagging - Homogenous ML models are used(Base Learners), are trained parallely, and they reduce the variance.
Boosting - Hetrogenous ML models are used(Base Learners), and are trained sequentially, the ouput of a model is given to the next model, and they help in reducing the bias of the model.
Stacking - Each Individual model parallely is trained on the ENTIRE DATASET, and the ouput predictions of the model are given to the next stage models, when they are re-trained on the models in stage 2, finally trained on a single power model, known as Meta-Classifier, in my case I used Logistic Regression.
