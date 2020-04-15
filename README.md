# To Churn or No to Churn

**The Project:**
  For our module 3 project we had a choice of three different data frames that would exercise our knowledge of classification problems when dealing with real world data.


**The Goal:**
  The focus of this project was to build a classification model that is able the predict on the set target of a data frame. Our business problem was binary so our target wasn't hard to distinguish from the rest of the data. 


**The Problem:**
  As the world continues to expand, so does our need to communicate. This is why telecommunication companies are so important, they keep us in touch with one another. With the amount of options your companies offer when it comes to communication, a loyal customer is bond to form amongst the customers you cater to. But that is just an assumption! What if you could tell if a particular customer would churn or not? What if you could predict the loyalty of the people you provide services for? Well my telecom friend you are in luck!!


**The Solution:**
  The top two things when it comes to a business are both making saving money & making money. So if we could tell you who amongst your customer roster will discontinue their services with you, you could create a focus group for that newly discovered roster. From there you could work on potential loyal customers who may just need a little more love when it comes to their services. But before you show them some love you need to find out who needs it first, and that is where our model comes in and predicts who will churn on you. 


**The Process**

The plan of attack was to do the following:
1. Explore & Clean data 
2. Transform data 
3. Model the data


*The Data:*
   The data was provided by the Kaggle member david_becks which consisted of collected data on churns in telecommunication data.
  
 *The Metrics:*
  For the metrics we chose Accuracy Score and the ROC AUC Score, you can find more information on the scoring metrics in the resource section located at the bottom of the READ.me.


*The Baseline Model:*
  The baseline model we chose to go with was the Random Forest Classifier because it handles imbalance and multicollinearity in the data. In the repository guide located at the bottom of the READ.me you will find the notebook that contains the cleaning, transforming, and exploring of the data, as well as the baseline model, along with a Decision Tree Classifier model. 


*Logistic Regression*


*Gradient Boost & AdaBoost:* 
  The two methods above fall under the ensemble category of modeling. We wanted to give the two models a try to see how they would perform. Boosting in general trains decision trees iteratively so that the next tree it builds makes up for the weakness of the previous tree (improving each tree one at a time vs. all at once --> random forest does). In the repository guide located at the bottom of the READ.me you will find the notebook that contains booth gradient boost and adaboost.  


*Encoders:*


# Conclusion

# Future Recommendations

# Repository Guide


# Team Members 

1. **Boi Moriba:**  https://github.com/bmor2552  

2. **Takehiro Yasuoka:** https://github.com/Tyasuoka


# Resources

**The Data:**
  Below is the direct link to our data source.
  
  https://www.kaggle.com/becksddf/churn-in-telecoms-dataset


**The Metrics:**
  The links below will contain documentation on ROC_AUC and Accuracy Scores.
  

*ROC_AUC Score:*  https://scikit-learn.org/stable/modules/generated/sklearn.metrics.roc_auc_score.html
 
 
*Accuracy Score:* https://scikit-learn.org/stable/modules/generated/sklearn.metrics.accuracy_score.html?highlight=accuracy#sklearn.metrics.accuracy_score
  
  
**Models:** Below you will find model documentation
  
  
*Random Forest:* https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html
  
  
*Decision Tree:*  https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html
  
  
*Logistic Regression:* https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html 
  
  
*Gradient Boost:* https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingClassifier.html
  
  
*AdaBoost:* https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.AdaBoostClassifier.html
  
 
 # Human Resources 
  
  Lindsey Berlin DS 02-17-2020 Coach
  
  
  Bryan Arnold DS 02-17-2020 Lead Instructor
  
  
