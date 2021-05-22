# Loans: The Financial Two-Way gift between Savers and Borrowers
## by (Ahmad Alashmony)


## Dataset

> Had you ever tried to take a loan from any resource, ex. a Family member, a Friend, your Boss, your mates or even the place you work. It's not easy for anyone to borrow or to lend but, for financial institutions it's totally different. Moving money forward in time (Saving) and getting money backward in time (Borrowing) is the core business here. But There's Some Questions to answer here like:
1. Who to lend?
2. How much risk would I face?
3. What's the suitable (Expected Return) to face those risks?
4. Can Diversification grow-up my return (on Actual Basis not just as expected)?
5. What's the (Expected Return) for each industry?

> More and more Questions like this can be answered using Financial data Analysis. In this database which contains about 114K records about loans I'll get more data about the Borrowers, loans the Customers and maybe some Economic conditions.


> Who want to get the most suitable return on his investment, must study the return and the risk and make a portfolio diversified well to have the best mix. This rule contains all financial institutions incluing commercial banks, They have to diversify their loan portfolio. This database contains the majour data that affect such financial decisions like Credit Quality which describe risk, Interest rates which describe the return, reason of loan, Loan Amount, Borrower State, Borrower Occupation and the customer's Employment status duration those can help to make diversified portfolio based on borrowers data and some other data like Location, and The pupose of loan and so on. Here's the most important analysis can start. 



## Summary of Findings

### 1. In this section, we'll investigate distributions of general indicators of economics and the Boeeowers. If there's unusual points or outliers, we'll a deeper look to clean things up and prepare to dig deeper at relationships between variables. 

####  In general, What's the interest rate(s) that seems to be the most common (Might be one used for retail customer)::
> Here I found the most used rates between 12% and 22%, but I can still notice that between 34% and 36% and it's a huge amount (Looks like the double value of the most used after cheching it I foun them with a bad credit rating, the debtor were about to default (or defaulted in some cases).

#### Then, I checked the most reason for taking a loan, it's an indicator for the demand on our products:
> Here I found a strange point, Most of loans wasn't for new customers, it's just refinancing the old ones (Debt Consolidation). We have to recheck credit policy in the Lender, Credit officers targets timing of collecting data and our database quality if needed. Another indicators here in the second and third highest rating, those are N/A and Other which is meaningless and might indicate bad data quality. This took me to dig deeper in it in with looking to customers financial capabilities using thier loans amounts, their Occupations and where they live, There was also additional exploration in bivirate section. 

#### What's our customers size, we will take the Loan Amount as a good indicator, We can see more later:
> Here I found that customers are retail or SMEs, A funny fact also appeared here: Most poeple like loans in 5x form (5,10,15,20,25, and it's on the 30 and 35 is outside our limit also).

#### What is our customers Occupation?
> Most of them are unidentified (Others and Professionals), That might refer to a bad data quality or a very diversified customers.

#### Where they live?
> Here I found that states with better economy on top of this list.


### 2. Second step was to check the relation between those indicators and each other and we'll dig deeper into the main defaulting indicators:

**- General Indicators and digging deeper with data about interest rates ouliars and why we have a lot of Debt Consilidation loans and what if this affect credit quality of the portfolio:**

#### What's the affect of credit Quality on Interest rate, We have 2 Credit rating methods (Before and after 2009):**
> It was very clear how credit Quality affect Interest rates before and after 2009 (and the Financial Crises in 2008 also), With higher risk the bank asked for higher interest rates (Rquired rate of return).

#### What's the affect of Loan Amount on Interest rate:
> At first look it's like the points was very well ditributed but, after a deep look we can fing it's afficting the interest rate it a little bit. The Larger the customer is the better interest rate he gets. For Example I couldn't't see interest rate above 18% for customers who get a loan more than 25K.

 #### What's the Credit Rating for customers requesting a Consolidation Debt:
 >Here's I found a useful info, most of those requests was accepted after changing the calculation method on different credit rating levels but, this change came after the World Financial Crises with a few months. I also found a normal indicator: the customers with Extremely High Credit Rating less in Debt Consolidation requests (according to their high solvency) and the customers with Extremely low credit Rating less also as they might default before they can request.
 
#### What's the Status of Loans on every Category?
> Here's the surprize, It seems like Debt consolidation loans were performing well!


**So, What's the most defaulting Loan categories?**
> It seemed like the Debt Consolidation wasn't the most deafulting loans although it has the most count, I want to dig deeper into the defaulting factors.

**- Defaulting factors, what's the relation between defaulting and:**
#### Borrower State:
> The most states in loans, seems like to be the most to default.

#### What's the rating of defaulting customers, for pre and after Jun 2009 credit rating methods:
> It's related on the Old Risk Rating method more than the new one, Or might be because we made a good Debt Reconsolidation agreements with them.

#### What's the occupations of the most defaulters?
> Others and professionals are still on the top, The top borrowers and the top defaulters.

#### Is defaulting more related to the duration they had in their jobs?
> It's better to look here, Older Employees has better salaries and also has a stable job and their possibility to default is lower.


### 3. Lastly, we'll check The importance of collaterals such as income prove or Mortgage to both Loan Amount and Interest Rate. and What could happen if we applied high interest rate on a Larger loans.


#### Now, It's the time to find out what's the importance of providing income verification to the Loan Amount and the Interest rate!


> It was clear to see Income verification is very required for loans above 25K, and it's very expected to get a lower Interest rate if we have income approval 


#### And what's the importance of providing a collateral like mortgage to the Loan Amount and the Interest rate!

> It's also important to provide a collateral such as mortgage to get a big loans.

#### Is there any relation between defaulting and the high interest rates on every loan amount?

> Although There's a very few loans defaulted for amounts higher than 25K and interest rates lower than 10% and although They had not also charged off, It seems like there's no relation as the Loans above 25K are actually too few in the database and most interest rates over 10%.


## Key Insights for Presentation

> Defaulting is not related to customer proprieties such as risk rating and Employment duration not to Loan properities such as Amount, reason or even interest rates applied to it.
> Changing loan properities to satisfy customers needs and abilities (Like debt consolidation) will help to keep customers performing well and growing economy.
