# Prediction with Decision Tree
***

### Projects:

Predicting the purchase of Iphones on the basis of gender, age and salary.


### Objectives:

Exploring Insights/Inferences by performing EDA on the given data. Relevant graphs were plotted to get some insights on data using seaborn package. Model fitting via Decision Tree by Importing sklearn package. 
***

### Python Libraries Used:
   * Pandas
   * Numpy
   * Matplotlib
   * Seaborn
   * Scikit learn
   * Joblib

***

### Methodology:
 1. Data copying and cleaning:
    * Read the csv file
    * copy the data
    * check for null values and other informations
    * drop the duplicate values
 
 2. Exploratory Data Analysis:
    * Conduct all the necessary EDA using various graphs on the dataset
    * interpret the graphs
    * check for outliers and correlation among the coloumns
    * perform one hot encoding in case of categorical columns

 3. Sampling of data:
    * Divide the data into x and y
    * standardize the data using StandardScaler lib
    * import test_train_split from sklearn.model_selection
    * divide the data into training and testing


  4. Modelling of data:
     * import DecisionTreeClassifier and initialize it
     * fit the model
     * predict the model

  5. Model validation (Error Calculation):
     * From sklearn.metris import accuracy_score, precision_score, confusion_matrix
     * check the accuracy of the model

  6. Save the Model:
     * import joblib
     * save the model

  ***
  ## Iphone Purchase data Probelm: 
  
  *File name: Iphone-purchase-data files*
  
  #### EDA Inferences:
  * There are total 198 and 182 Females and Males, respectively.
  * Out of 198 females, 77 has purchased Iphones while out of 182 males, 63 has purchased Iphones.
  * Females have purchased more Iphones compared to males.
  * Genders with more salary are likely to purchase Iphones.
  * Females have more salaries and hence purchased more Iphones than males.
  * Genders with high salaries in 27-45 years of age have purchased Iphones.
  * Genders having age group above 45 years purchased Iphones irrespective of their salaries.
  * The data is normally distributed in all the cases. The skewness is calculted to be 0.23, 0.46 and 0.54 for age, salary and purchase Iphones, respectively.
  * The correlation of age and salary with the Iphone purchase is 62 and 38%, repectively.
  * There are not outliers present in the data.


 
  #### Decision Tree Model Results:
  The accuracy of the model is came out to be:
  
  **Accuracy Score: 0.92**

  **Precision Score:0.92** 
  
***  



       
      
     
     
     

