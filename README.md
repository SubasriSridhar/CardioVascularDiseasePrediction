Objective:
The objective is to build a model which predicts the risk of cardiovascular diseases in the population that will help the doctors to proceed with the treatment.

Methodolgy:
After the initial phase of data preprocessing i.e data cleaning,feature extraction and transformation, the data exploration was done to see if there are any patterns or features which clearly distinguishes the non-cardiac and cardiac patients. In this process, it was found that there were few outliers in the data and each feature was handled differently to correct the outliers. Then the data was fed to different models such as decision tree, random forest, logistic regression , multinominal naive bayes classifiers and then into ensemble models. Each model was trained and the complete performance of the model was evaluated using different performance metrics like classification accuracy , confusion matrix. Parameters such as Accuracy, Precision, Recall and F1-score were estimated to analyze the performance and a comparative study of these classifiers was carried out.
I have chosen the performance metric to be Recall, since the idea of false positives is far better than false negatives. I’d rather get some healthy people considered patients over leaving a patient considered healthy. Misclassification is a risk that the model could not afford as it deals with lives, irrespective of the cost of the model.For the process of achieving optimised model, hyperprameter tuning techniques were used to optimise the parameters using grid search.


The results of the model yields best performances when compared to the base line model. The recall score for the people prone to heart disease is close to 80%.

Future research:
This project was constrained by time and other resources. The outcome of the project is not conclusive but it's a good start. Due to the time constraints, only the basic models were tested and implemented. However, there are many other sophisticated models such as SVM, SGD classifiers, KNN and on top of that there are many more boosting techniques. The training of the model could be better seen with ROC-AUC curves as performance metrics. In addition to all of these implementing dimensionality reduction techniques like T-SNEE or PCA could improve performance.

References:
https://www.kaggle.com/sulianova/cardiovascular-disease-dataset
https://www.kaggle.com/benanakca/comparison-of-classification-disease-prediction
