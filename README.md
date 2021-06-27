# Expected-Loss-Analysis-on-Lending-Club-Data
LendingClub Corp. is an online lender who makes loans online to consumers and sells the loans to investors. The product is a fixed rate, 3 or 4-year fully amortizing term installment loan.
\\
\\In this project, we analyze the loan data of LendingClub from the year 2007 to the second quarter in 2019. The data explores the demographic dimensions of personal loans and loan status (fully paid/ charged off), which is available on kaggle.
\\
\\Our goal is to identify the risk of unsecured personal loans. Specifically, a machine learning model was developed to predict the probability of full payment and charge off. On top of that, we utilize the model to predict the expected loan loss from current borrowers, providing insights about risk control and loss reduction.
\\
\\ In our model, to calculate the expected loss, we consider that the $LGD=100\%$, since if a customer defaults the club loses the entire amount and $EAD$ as the amount lended as it loses the entire amount, here we are taking a simple case and focusing mainly on building the PD model using the process described above. 
\\
\\ We first did a preliminary data analysis to look at the different features and then used logistic regression to find the probability of default. We also found a interesting linear relationship between interest rates and default rates. The code and the numerical results are explained in the jupyter notebook attached.
