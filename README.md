<h1 align="center"> Bank Loan Default Prediction </h1> 
<img align="center"  height="450" width="450" src="https://media.istockphoto.com/vectors/default-vector-id1150806061?k=20&m=1150806061&s=612x612&w=0&h=qd1FbSpVAw2DoKDkwiRQf70qOVAlkmHuHm886r1K340=" >


## 1.0 Summary

- [Analysis Notebook](https://github.com/lhtreis/Bank_Loan_Default_Prediction_Hackathon/blob/main/Bank_Loan_Default.ipynb)

## 2.0 Context

<p> This is a hackathon dataset from the MachineHack website
 
## 3.0 Business Challenge

<p> The objective of this project is to predict if a person will become a loan defaulter or no through the data analysis 
  
## 4.0   Solution Strategy:

<b>Step 01.</b> Colect the dataset from Kaggle;

<b>Step 02.</b> Clean, organize and, through descriptive statistics, understand the data at hand;

<b>Step 03.</b> Define new relevant variables for data analysis, label encoding of cathegorical variables and numeric variables scaling;

<b>Step 04.</b> Create a machine learning model that is effective for unseen data;

## 5.0 Solution 

<b>Used tools?</b>
- Python 3.8
  - Statistical techniques for descriptve analysis, implementation of various ML algorithms through cross validation with logloss metrics 
- Jupyter Notebook
 

## 6.0 Conclusion

This project is not yet finished. So far, the accuracy of the implemented ML models is not acceptable. For some algorithms there is a overfitting (XGBClassifier, RandomForestClassfier, LGBMClassifier) while for others there is a underfitting (SVC, LogisticRegression, KNeighborsClassifier). 
This project made it possible to learn and experience some tools and processes, such as: cross validation, label encoding, variable scaling and ML models hyperparametrs tuning.

## 7.0 Next steps:

- [ ] Solve the under/overfitting problem
- [ ] Find the best features to optmize the ML model
- [ ] Optimize cut-off point for ML model
  
## 8.0  References

- [Avaliação de Risco de Crédito com Machine Learning](https://medium.com/data-hackers/avalia%C3%A7%C3%A3o-de-risco-de-cr%C3%A9dito-com-machine-learning-3b1dc4d29d5f) 

