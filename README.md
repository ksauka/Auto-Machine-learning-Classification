# Auto-Machine-learning-Classification
Auto-Machine-Learning-Practice
This is a program that make it possible to automatically run different combinations of :
Various data scaling methods and encoding methods
Various values of the model parameters for each model
Various values for the hyperparameters
Various numbers 𝑘 for 𝑘-fold cross validation

Scalers  List : 
[StandardScaler(), MinMaxScaler(), MaxAbsScaler(), RobustScaler()] 
 if you want to scale other ways, then put the sclaer in list

 Encoders list 
  [OrdinalEncoder(), OneHotEncoder(),SVC(),]
    if you want to use only one, put a encoder in list

  Models list 
  [DecisionTreeClassifier(criterion='entropy'),DecisionTreeClassifier(criterion='gini')  ,LogisticRegression(),SVC()]
 if you want to fit other ways, then put the model in the list


