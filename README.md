# Heart Disease Prediction

In this model we have predicted the risk of heart disease based on real dataset that we got from a medical university chennai.

**DATASET**

  The dataset we used contians more than 150 patient records and their daily routine data.
  As a result it helps  our model to train with realtime data.Our data set contains many features like age,Dietary hahbit,Alcohol consumer or not etc...
  
 **Data Preprocessing:**
 
    We have preprocessed our dataset using Sk-learn.
   **sk-learn:**
          The sklearn.preprocessing package provides several common utility functions and transformer classes to change raw feature vectors into a representation that       is more suitable for the downstream estimators. 
          
          In general, learning algorithms benefit from standardization of the data set.
          
**Models Used:**          
          
1. **SVM**
2. **Naive Bayes**
3. **Logistic Regression**
4. **Decision Tree**
5. **Random Forest**
6. **LightGBM**
7. **XGboost**

**Model's Result Prediction Percentage:**

**SVM:**
    Support Vector Machine
    
        ~Training Set Prediction : 0.6694214876033058
        
        ~Testing Set Prediction : 0.5737704918032787
    
**Naive Bayes:**
    Works based on Naive Bayes algorithm
    
        ~Training Set Prediction : 0.8677685950413223
        
        ~Testing Set Prediction :  0.7868852459016393
        
**Logistic Regression:**
    Logistic regression estimates the probability of an disease  based on a given dataset of independent variables
    
        ~Training Set Prediction : 0.8636363636363636
        
        ~Testing Set Prediction : 0.8032786885245902
        
**Decision Tree:**
    A decision tree is a non-parametric supervised learning algorithm, which is utilized for both classification and regression tasks.
    
        ~Training Set Prediction : 1.0     
        ~Testing Set Prediction :  0.7704918032786885 
        
**Random Forest:**
    Works based on Naive Bayes algorithm
    
        ~Training Set Prediction : 1.0
        
        ~Testing Set Prediction : 0.7704918032786885

**LightGBM:**
     Gradient Boosting Decision Tree (GBDT) algorithm with the addition of two novel techniques: Gradient-based One-Side Sampling (GOSS) and Exclusive Feature Bundling (EFB).
    
        ~Training Set Prediction : 0.9958677685950413
        
        ~Testing Set Prediction :0.7704918032786885
        
 **XGBoost:**
     It builds a decision tree for a given boosting iteration, one level at a time, processing the entire dataset concurrently on the GPU.
    
        ~Training Set Prediction : 0.987603305785124
        
        ~Testing Set Prediction : 0.7540983606557377      
   
 
 





Dataset : https://archive.ics.uci.edu/ml/datasets/Heart+Disease



Shrijayan R A 

Shangameshwar K

