## R_Functions
Author: Brian Scott

## Credentials: 
BS in Economics, Bradley University (Peoria, IL)
  
MS in Applied Economics and Data Intelligence, University of Nevada: Las Vegas           
  Graduation: December, 2022
     
## Project Purpose

This repository includes functions I have made in the R coding language. The main goal of these functions is to increase the speed of statistical analysis. The code is presented in the form of R markdown files, and the link to each specific function in RPubs is posted for each function. For a better visual expirience, use the RPub links. 


#### RPubs Full Cite Link: https://rpubs.com/BrianScott



## Log_Lag Function
#### RPubs Log_Lag Link: https://rpubs.com/BrianScott/948426
#### Purpose
This function quickly logs and lags a dataset, knowing to only log columns with all positive values, in order to avoid NA's. 
The primary use of this function is for the variable selection in regression models. This allows someone to quickly navigate through logged, raw and lagged model versions.  



## Corr_Reduce Funtion
#### RPubs Corr_Reduce Link: https://rpubs.com/BrianScott/948474
#### Purpose
This function helps to reduce the amount of potential variables for a regression model. The model produces a Full Datset Correlogram, a bar chart of significant variables, and a reduced correlogram of only the significant variables



## LM_DIAGNOSTIC Function
#### RPubs LM_Diagnostic lnk: https://rpubs.com/BrianScott/948499
#### Purpose
This Function does several tests at once to determine if a linear model s approprate for the regression equation. In addition to the standard output such as the r Square and pvalues, the function also uses plots and tests to determine heteroskedacity, autocorrelation, and multicoliniarity.

#### Side Note
This function does test well for outliers, I am still researching the best approach to test for outliers. 
This function does not do hold out test sampling, I wil provide another function for that.
Hold out sampling should only be done on models that fit all the requirements for linear regression, so the LM_DIAGNOSTIC Function is used to determine if hold out testing is necessary 
