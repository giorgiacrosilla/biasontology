# Mental Accounting

### <mark style="color:red;">C</mark>ontext literature and state of the art
<figure><img src="Mental-Accounting.jpg" alt=""><figcaption></figcaption></figure>

**Mental accounting** is a cognitive bias in which individuals categorize their financial resources and transactions into separate mental "accounts" based on subjective criteria, rather than considering the overall financial picture. This bias was first proposed by economist Richard Thaler. 
***

References:

{% embed url="https://en.wikipedia.org/wiki/Mental_accounting" %}

{% embed url="https://www.investopedia.com/terms/m/mentalaccounting.asp#:~:text=Mental%20accounting%20refers%20to%20the,the%20field%20of%20behavioral%20economics" %}

***
### <mark style="color:red;">L</mark>LM

#### Can you give me a definition of "Mental acocunting"?

Mental accounting is a cognitive bias in which individuals categorize their financial resources and transactions into separate mental "accounts" based on subjective criteria, rather than considering the overall financial picture. This bias was first proposed by economist Richard Thaler. 

#### Can you create 10 scenarios compelling with the bias?

Sure, here are ten scenarios illustrating mental accounting:

There are several key aspects to mental accounting:   

1. **Segregation of Funds**: Individuals mentally separate their money into different categories based on factors such as its source (e.g., salary, gift, inheritance), intended use (e.g., rent, groceries, entertainment), or time frame (e.g., short-term savings, retirement funds).   

2. **Perceived Utility**: People may attach different psychological values or "utility" to money in different mental accounts, which can affect their spending and saving behaviors. For example, money set aside for leisure activities might be considered more disposable than money earmarked for essential expenses.   

3. **Inconsistent Decision Making**: Mental accounting can lead to inconsistencies in decision making. For instance, someone might be willing to spend a large sum of money on a vacation (categorized as discretionary spending) but be unwilling to spend the same amount on a necessary home repair (categorized as an obligation). 

4. **Loss Aversion**: Mental accounting can also contribute to loss aversion, where individuals are more averse to losses in one account than they are motivated by gains in another. For example, someone might be more upset about losing $100 from their vacation fund than they are pleased about finding $100 in a pocket.  

5. **Difficulty in Optimizing Resources**: By focusing on individual accounts rather than overall financial health, individuals may miss opportunities to optimize their resources. For instance, they may not consider transferring money from a low-interest savings account to a higher-interest investment account because they mentally categorize the funds differently. 

Mental accounting can impact financial decision making in both positive and negative ways. While it may help individuals budget and prioritize spending, it can also lead to suboptimal choices and prevent people from making the most effective use of their resources. 

1. **Gift Money**: A person receives a cash gift for their birthday and mentally categorizes it as "fun money," deciding to spend it on entertainment or dining out rather than using it to pay bills or save. 

2. **Tax Refund**: Upon receiving a tax refund, an individual might categorize it as "extra money" and decide to splurge on a luxury item rather than using it to pay off debt or invest for the future. 

3. **Salary Bonus**: An employee receives a year-end bonus and decides to allocate a portion of it to a vacation fund, mentally separating it from their regular income and savings.   

4. **Windfall Gain**: Someone wins a small amount of money from a lottery scratch-off ticket and decides to use it to purchase something they've been wanting, rather than adding it to their savings or investment accounts.   

5. **Credit Card Rewards**: A person accumulates credit card rewards points and mentally treats them as "free money," using them to buy gift cards or merchandise instead of applying them toward their credit card balance. 

6. **Emergency Fund**: A household maintains a separate savings account labeled as an emergency fund, earmarking it exclusively for unexpected expenses such as car repairs or medical bills. 

7. **Vacation Savings**: A family sets aside a portion of their income each month into a dedicated vacation fund, ensuring they have enough money saved up specifically for travel expenses. 

8. **Retirement Accounts**: An individual contributes regularly to their retirement account, mentally treating it as money they won't touch until retirement, separate from their regular checking or savings accounts.   

9. **Mortgage Payment**: Homeowners may view their mortgage payment differently than other expenses, considering it as a form of forced savings or investment in their property rather than just a monthly bill.  

10. **Budgeting for Entertainment**: A couple allocates a fixed amount of money each month for entertainment purposes, such as dining out or going to the movies, and strictly adheres to that budget without dipping into other funds for such expenses.


#### Now consider the scenario "Tax Refund" and give me a short user story from it.

User Story: Tax Refund Splurge

As a recipient of a tax refund,
I want to embrace the opportunity to treat it as "extra money,"
So that I can indulge in a luxury purchase without financial guilt.

Acceptance Criteria:

* As a user, I anticipate receiving a tax refund after filing my taxes.
* I want to mentally categorize this tax refund as "extra money," separate from my regular income or savings.
* I want to feel liberated from using this refund to pay off debt or invest for the future.
* I want to explore options for indulging in a luxury item or experience, such as designer clothing, a fancy dinner, or a weekend getaway.
* I want to experience the joy and excitement of splurging on something special, knowing that it's a treat made possible by the tax refund.
* I want to share my excitement with friends or family, enhancing the celebratory atmosphere surrounding my tax refund splurge.

#### We can now derive example-based-CQs from the user story.&#x20;

1. How does the individual categorize the tax refund in terms of its use?
   * Extra Money Accounting.
2. What is the perceived value of the tax refund to the individual?
   * Extra Money.
3. What decision is taken by the individual?
   * Luxury Purchase.
  
#### If you should make an ontology based of the "Mental Accounting" which classes and properties would you create?

Creating an ontology for the "Mental Accounting Bias" involves defining classes to represent different concepts related to this bias and properties to describe the relationships and attributes of these concepts. Here's a basic ontology structure for the Mental Accounting Bias: 

  

### Classes: 

  

1. **Financial Transaction**: Represents a monetary exchange or activity involving money. 

2. **Financial Account**: Represents a designated fund or category where money is held or allocated. 

3. **Income Source**: Represents a source of money such as salary, bonus, gift, etc. 

4. **Expense Category**: Represents a category of expenditure such as groceries, entertainment, rent, etc. 

5. **Financial Goal**: Represents a desired financial outcome or objective. 

6. **Psychological Value**: Represents the subjective perceived value or utility assigned to money in a particular account or category. 

7. **Decision**: Represents a choice or action made by an individual related to financial management. 

8. **Time Frame**: Represents the temporal aspect associated with a financial account or transaction (e.g., short-term, long-term). 

  

### Properties: 

  

1. **hasTransaction**: Relates a financial account to financial transactions associated with it. 

2. **hasIncomeSource**: Relates a financial account to the source(s) of income deposited into it. 

3. **hasExpenseCategory**: Relates a financial account to the categories of expenses allocated from it. 

4. **hasFinancialGoal**: Relates a financial account to the financial goals it is intended to serve. 

5. **hasPsychologicalValue**: Relates a financial account to the perceived psychological value assigned to money within it. 

6. **hasDecision**: Relates a financial account to the decisions made regarding its management or use. 

7. **belongsToTimeFrame**: Relates a financial account or transaction to a specific time frame. 

8. **isCategorizedAs**: Relates a financial transaction or account to its categorization within mental accounting. 

9. **influencesDecision**: Relates a psychological value or financial goal to its influence on decision making. 

10. **relatesToBias**: Relates classes and properties within the Mental Accounting Bias ontology to the overarching concept of cognitive bias. 

This ontology provides a framework for representing the various elements and relationships involved in mental accounting bias, facilitating more structured analysis and understanding of this cognitive phenomenon. 

### Framester Frames used:

* [Deciding](https://w3id.org/framester/data/framestercore/Deciding)
* [CommercialTransaction](https://w3id.org/framester/data/framestercore/CommercialTransaction) 

 

