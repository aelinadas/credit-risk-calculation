# Credit Risk Calculation
<img alt="risk" src="https://github.com/aelinadas/credit-risk-calculation/blob/main/images/risk.png" />

### PROJECT DESCRIPTION
There are different kind of loans that a bank provides. 
Credit card and Home loans are one of the few kind of loans that a bank provides an individual or a financial institution.
The likelihood of a borrower would not repay their loan to the lender is known as **Credit Risk**.
The event of the borrower not being able to repay their debt is called **Default**.
In case of default, the lender will suffer a substantial loss which is called as **Expected Loss**.

Inorder to protect the bank against borrower debts, the lender access a Credit Risk associated with each borrower.

In this project, we have calculated the estimated **Expected Loss/Expected Credit Loss** that Lending Club institution would incur based on the consumer loans lent out by them. 

The following formula is applied to calculate the Expected Loss.
<p align="center">
<strong>EL = PD x LGD x EAD</strong><br />
<strong>EL - Expected Loss</strong><br />
<strong>PD - Probability of Default</strong><br />
<strong>LGD - Loss Given Default</strong><br />
<strong>EAD - Exposure at Default</strong>
</p> 

##### TERMINOLOGIES

**Expected Loss - The amount a lender loses incase a borrower defaults.**<br />

**Probability of Default - The borrower's inability to repay their debt in full amount on time.**<br />

**Loss Given Default - The proportion of the total exposure that cannot be recovered by the lender once a default has occurred.**<br />

**Exposure at Default - The total value that a lender is exposed to when a borrower defaults.**<br />

<p> We have built PD, LGD and EAD models and combined them to calculate the Expected Loss of the entire portfolio (Lending Club).</p>

---
### Data

Lending Club Consumer Loan issued from 2007 to 2015 was used as the dataset for this project. You can download the data from [Kaggle](https://www.kaggle.com/wordsforthewise/lending-club) 

---

### Project Structure

1. To know more details about the process of building the models in details please refer Programs folder, it contains the Jupyter Notebooks explaining the entire process.
	1. Data Preparation.ipynb - Details the process of data cleansing and extracting the data for building models
	2. Probability of Default Model.ipynb - Details the process of building Probability of Default(PD) model and validating its accuracy using **Gini and Kolmogorov coefficents**
	3. Expected Loss.ipynb - Details the process of building Loss Given Default(LGD) and Exposure at Default(EAD) models. Finally, illustrates process of combining all three models to calculate Expected Loss
2. Models folder contains PD, LGD Stage-I and LGD Stage-II models exported and saved with .sav extension

---

### LANGUAGE AND TOOLS

- Python
- Jupyter Notebook

### INSTALL AND RUN

- Install Jupyter Notebook
- Import the notebook(.ipynb) files into Jupyter Notebook