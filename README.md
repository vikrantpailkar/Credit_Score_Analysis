Credit Score Analysis in Python
=============
**A credit scoring model** is a tool that is typically used in the decision-making process of accepting or
rejecting a loan. A credit scoring model is the result of a statistical model which, based on information
about the borrower (e.g. age, number of previous loans, etc.), allows one to distinguish between "good"
and "bad" loans and give an estimate of the probability of default.

**Loan Default**: In finance, default is failure to meet the legal obligations of a loan, for example when a home buyer fails to make a mortgage payment, or when a corporation or government fails to pay a bond which has reached maturity.

**Steps Involved**
=============
* Part 1 - **Data Processing**: Cleaning and Transforming Raw Data into the Understandable Format
* Part 2 - **Profiling**: Data profiling is the process of examining the data available from an existing information source (e.g. a database or a file) and collecting statistics or informative summaries about that data.
* Part 3 - **Logistic Regression Model**: In statistics, logistic regression(or logit regression), is a regression model where the dependent variable is categorical. This article covers the case of a binary dependent variable—that is, where the output can take only two values, "0" and "1", which represent outcomes such as pass/fail, win/lose etc.
* Part 4 - **Decision Tree Model**
* Part 5 - **Clustering Analysis**
* Part 6 - **Principal Components Analysis**

------------
The raw dataset is in the file **"CreditScoring.csv"** which contains 4455 rows and 14 columns:

<table>
<tbody>
<tr><td><b>1  Status</b></td> <td>credit status</td></tr>
<tr><td><b>2  Seniority</b></td> <td>job seniority (years)</td></tr>
<tr><td><b>3  Home</b></td> <td>type of home ownership</td></tr>
<tr><td><b>4  Time</b></td> <td>time of requested loan</td></tr>
<tr><td><b>5  Age</b></td> <td>client's age </td></tr>
<tr><td><b>6  Marital</b></td> <td>marital status </td></tr>
<tr><td><b>7  Records</b></td> <td>existance of records</td></tr>
<tr><td><b>8  Job</b></td> <td>type of job</td></tr>
<tr><td><b>9  Expenses</b></td> <td> amount of expenses</td></tr>
<tr><td><b>10 Income</b></td> <td> amount of income</td></tr>
<tr><td><b>11 Assets</b></td> <td> amount of assets</td></tr>
<tr><td><b>12 Debt</b></td> <td> amount of debt</td></tr>
<tr><td><b>13 Amount</b></td> <td> amount requested of loan</td></tr>
<tr><td><b>14 Price</b></td> <td> price of good</td></tr>
</tbody>
</table>
