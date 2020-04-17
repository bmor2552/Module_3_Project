# To Churn or No to Churn

**The Project:**
  For our module 3 project we had a choice of three different data frames that would exercise our knowledge of classification problems when dealing with real world data.


**The Goal:**
  The focus of this project was to build a classification model that is able the predict on the set target of a data frame. Our business problem was binary so our target wasn't hard to distinguish from the rest of the data. 


**The Problem:**
  As the world continues to expand, so does our need to communicate. This is why telecommunication companies are so important, they keep us in touch with one another. With the amount of options your companies offer when it comes to communication, a loyal customer is bound to form amongst the customers you cater to. But that is just an assumption! What if you could tell if a particular customer would churn or not?


**The Solution:**
   If we could tell you who amongst your customer roster will discontinue their services with you, you could create a focus group for that newly discovered roster. From there you could work on potential loyal customers who may just need a little more love when it comes to their services. But before you show them some love, you need to know who needs it first, and that is where our model comes in.


**The Process**

The plan of attack was to do the following:
1. Explore & Clean data 
2. Transform data 
3. Model the data

**In the repository guide located at the bottom of the README you will find the links to the notebooks & csv files for the following descriptions:**  


***The Data:*** The data was provided by the Kaggle member david_becks which consisted of collected data on churns in telecommunication companies.


***The Metrics:*** For the metrics we chose Accuracy Score and the ROC AUC Score.


***The Baseline Model:*** The baseline model we chose to go with was the Random Forest Classifier because it handles imbalance and multicollinearity in the data. 


***Logistic Regression:*** We tried using the encoders below as well as balacing the data by using the class_weight parameter. 


***Gradient Boost & AdaBoost:***  These two methods fall under the ensemble category of modeling. We wanted to give the two models a try to see how they would perform. Boosting in general trains decision trees iteratively so that the next tree it builds makes up for the weakness of the previous tree (improving each tree one at a time vs. all at once --> random forest).


***Encoders:*** To enhance our model we tried both OneHot and Target Encoding.
  


# Conclusion
Gradient boosting has given us the best ROC_AUC score when predicting the target. 


# Future Recommendations

1. Build a model that is able to classify the *"low hanging fruit"* of the churn group. This way the telecommunication companies can focus on the customers who they **most certainly** can convince not to churn.  

2. Conduct another analysis after collecting more data. We can then help telecommunication companies develop packedges that will save the customer money and decrease the number of churning customers. 

3. Use Feature Importance on our model to remove  the variables that are hurting the results. 


# Repository Guide

***Notebooks***

Data Clean Up With Baseline Model: https://github.com/Tyasuoka/Module_3_Project/blob/master/Jupyter_Notebook/%20Customer_Churn_Baseline.ipynb

Gradient Boost & AdaBoot: https://github.com/Tyasuoka/Module_3_Project/blob/master/Jupyter_Notebook/Gradient_Boost_AdaBoost.ipynb

Logistic Regression With Encoding: 
https://github.com/Tyasuoka/Module_3_Project/blob/master/Jupyter_Notebook/Mod_3_Baseline_Log_Reg.ipynb

Encoders On Random Forest Gradient Boost & AdaBoost: https://github.com/Tyasuoka/Module_3_Project/blob/master/Jupyter_Notebook/OneHot_Target_Encoders.ipynb

***CSV Files***

Original Data: https://github.com/Tyasuoka/Module_3_Project/blob/master/CSV_Files/Telecom_churn.csv

Cleaned Data: https://github.com/Tyasuoka/Module_3_Project/blob/master/CSV_Files/Cleaned_Churn_Data.csv

**Presentation**
https://www.canva.com/design/DAD5FkbTvBA/EENajulaT4BcXTQAhPN3rQ/view?utm_content=DAD5FkbTvBA&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink


# Team Members 

1. **Boi Moriba:**  https://github.com/bmor2552  

2. **Takehiro Yasuoka:** https://github.com/Tyasuoka


# Resources

**The Data: Below is the direct link to our data source.**

https://www.kaggle.com/becksddf/churn-in-telecoms-dataset


**The Metrics: The links below will contain documentation on ROC_AUC and Accuracy Scores.**
  

*ROC_AUC Score:*  https://scikit-learn.org/stable/modules/generated/sklearn.metrics.roc_auc_score.html
 
 
*Accuracy Score:* https://scikit-learn.org/stable/modules/generated/sklearn.metrics.accuracy_score.html?highlight=accuracy#sklearn.metrics.accuracy_score


**Models: Below you will find model documentation**


*Random Forest:* https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html
  
  
*Decision Tree:*  https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html
  
  
*Logistic Regression:* https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html 
  
  
*Gradient Boost:* https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingClassifier.html
  
  
*AdaBoost:* https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.AdaBoostClassifier.html
  
 
 
 # Human Resources 
  
  
 Lindsey Berlin DS 02-17-2020 Coach
  
  
 Bryan Arnold DS 02-17-2020 Lead Instructor
  
  
