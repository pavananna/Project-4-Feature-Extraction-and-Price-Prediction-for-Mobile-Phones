# Project-4-Feature-Extraction-and-Price-Prediction-for-Mobile-Phones
1) Import Dataset:
       For importing the dataset First we have to import the pandas and then we have to use code:
             pd.read_csv("file path")
   
3) Cleaning the dataset:
        For cleaning the dataset we have find any null value are there are not for that we have use:
             d1.isnull().sum()
        then remove the unwanted rows like 'UNAMED:0'
   
5) Feature Engineering:
      If we see the dataset The model Column contain both the Company name and then model of the phone , so we have to split 
      the column into two parts as company_name as well as Model.
   
7) Finding Outliers:
      If we see the Prize column the  Min and Max value has so Much difference So there is a chance of outliers , so First we
      have to remove those For That use IQR Method.
   
9) Normalization:
      If we see the dataset som columns have values like 0 ,1 some columns have values 20000 so there is huge difference so
      we have to use MIN - MAx Sacaler Techinuque  to minimize the values.
   
11) Handling Categorical Data:
      For implementing the meachine learning models we have to cahnge the categorical data into numeric data so for that i
      have used the Label Encoder for the columns Prize , Model, Company _Name, Bateery.
    
13) Meaching Learning Models:
      For Traning the model i have used KNN Regressor, Linear Regression, Decision Tree, Support Vector Meachine, Random 
      Forest in that Random Forest is the best Model. 
14) Finding the Feature Importance:
      For Finding which Fature is Important i have used First Correlation, then ploat the bargraph, scatter plot from that
     when the memory is 110gb , RAM is 8GB, Battery is 5000 and AI lens is 0.00 , Mobile Height is 17 0r 18 the Prize is 
     high.
