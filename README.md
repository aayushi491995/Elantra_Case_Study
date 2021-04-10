# Elantra_Case_Study
Predict the sales and prepare a Linear Regression Model for the same.

### Dataset
This project is meant to explore, analyse, visualize and predict the sales of the store:
      1. Month
      2. Year
      3. ElantraSales - taget variable to predict the sales using 
      4. Unemployment
      5. Queries
      6. CPI_energy
      7. CPI_all 

Machine Learning Steps Follwed to acheve the objective.
1. Import necessary Libraries
2. Read the csv dataset
3. Check for the null values and the unwanted values in the dataset
     - We checked for the null values and unwanted values in the dataset there were none.  
4. Split the Train and Test data based on the years.
     i. Train dataset - records with year less than or equal to 2012
     ii. Test dataset - records with year more than 2012
6. Train Test Split the dataset.
7. Create a Linear Regression model.
9. Performance of Test data 
     - Score - 0.55387
     - RMSE  - 2966.29744
     


