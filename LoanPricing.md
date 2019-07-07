## Loan pricing

The loan size is determined by the course fees and living expenses as estimated by the university. The estimated minimum amount required for board and lodging by students not in university accommodation is R84,500. Students may borrow any amount up to this maximum amount. Students may also wish to pay a deposit, thereby reducing their loan-to-value (LTV) ratio. A lower LTV may result in a more favourable interest rate.

Once the maximum loan size is calculated an affordability assessment will be done to calculate how long it will take them to repay the loan. Inputs to the calculation are the students probability of employment ,projected income, and interest rate.
### 1.	Probability of employment

#### (i) Student level

Where good quality student-level data exists a model will be trained to predict employment within 6 months of graduation. Data must be of good quality, and come from a reputable source, and have a sample size sufficient for making robust predictions.

#### (ii) Course level
In the absence of sufficient, and varying student-level data a course level estimation will be used. 
This estimation will be based on university survey data. In the case of UCT, data from Centre for Higher Education Development (CHED) will be used. The minimum employment rate in the last 3 years will be used as a conservativ estimate.

#### (iii) Stats SA Quarterly Labour Force Survey
In the absence of granular data ( (i) & (ii)) the most recent Quarterly Labour Force Survey (QLFS) data will be used.
For Q1 2019 the unemployment rate for graduates is 7.9%.

![QLFS](https://user-images.githubusercontent.com/37291723/60772378-ce4b8c00-a0f5-11e9-8c5e-68650c81d01e.png)

#### (iv) Exceptions
Where a student has a confirmed job offer, or internship the probability of employment will be adjusted to 1.

### 2.	 Projected income
Income will be estimated using the same process as the employment estimation - a model, or survey data.
### 3.	Interest rate

The interest rate will be linked to the students risk profile. The lowest interest rates will be reserved for the students with the highest probability of employment, and the highest to those with the lowest probability of employment. A lower LTV ratio will also result in a lower interest rate, encouraging students to also have a stake in their education.

An illustration of interest rates, by risk profile.

<img width="472" alt="table1" src="https://user-images.githubusercontent.com/37291723/60772552-516de180-a0f8-11e9-8458-3a4c88af2e81.PNG">


The level of interest rates will be dependent on investors desired internal rate of return (IRR).

### 4.	Affordability calculation

Using the interest rate, loan size, and projected income we can calculate the maximum loan size a student can afford. 
Based on the projected income we can estimate the maximum monthly instalment the graduate can afford. We assume 20% of the salary may be used for the student loan.Given that most students do not have existing credit we believe this is a conservative estimate.

An illustrative example:

Projected gross annual salary  R300,000


Monthly salary 		R25,000

Income Tax			  R4,021

Net Income			  R20,979

Instalment available 		20% x R20,979 = R4,195

Assuming a probability of employment of 97.50% and LTV of 60%, the interest rate offered would be 4.46%. 
This rate is used to calculate the maximum loan size over various terms as illustrated below:

<img width="242" alt="table2" src="https://user-images.githubusercontent.com/37291723/60772582-d9ec8200-a0f8-11e9-9324-3a5ba4639605.PNG">

Assuming the student above is registering for a MComm in Economics the student would have a CoA of R154,520 (R70,020 Tuition + R84,500 living expenses).


CoA 					    	R154,520

40% stake					  (-R61,808)

Finance required		R97,212

Finance offered 		R97,212


In the example above the student would be offered a loan of R97,212 paid directly to the university over 27 months. 
 
## Repayment structure
Loan repayment terms describe the timing, frequency and size of payments

Repayments begin when the student starts to work or 6 months after graduation, whichever is sooner. The monthly instalment is fixed as per calculations above. Repayments are made monthly via direct deposit or debit order to ensure timely collection. Students who select debit order can be rewarded by a decrease in interest rate, or allocation of Khanyezi tokens.

Assuming the student above begins payment 18 months after the loan is originated (12 months study + 6 months job search), the repayment schedule would be as follows:

January 2020 :Loan Amount   	    	R97,212

July 2021:Outstanding balance		R105,284.60

Monthly repayment 				          R4,146.56

Term						                    27 months


 ![PIC1](https://user-images.githubusercontent.com/37291723/60772408-37330400-a0f6-11e9-8d17-cc7b385c2b1d.png)

 

Student-level loan terms, expected and realised payments will be tracked securely in Khanyezi.LoanRepayments.sol.


