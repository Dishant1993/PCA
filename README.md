# PCA
Principal Component Analysis
Lending is one of the critical functions of any bank or financial institution. 
Customers are provided loans across different products (home loan, loan against property etc.) at competitive interest rates for an acceptable tenure. 
There is always a risk that a customer may default on the loan or may try and repay the loan in advance which leads to financial losses to the business.
There may not be enough data or evidence available from the past which will help the firm to predict the loan default or prepayment and mitigate the above possible risk.
However, it does have information about the customer demographics, loan details, EMI transactions etc. which contributes to more than 25-30 features (high-dimension data) related to a customer’s loan account. 
But due to high dimensions it is difficult to identify any patterns within the data. 
Unsupervised learning techniques like Principal Component Analysis comes to rescue here to reduce the high dimensionality and help in further analysis and pattern recognition.
Data file contains information about the loan transactions done by the customer.

All important details regarding the loan i.e. loan amount, interest rate, outstanding principal, loan to value ratio (Net LTV), tenure, city where the loan was originated etc. has been provided.

Some of the features that correspond to multiple loan transactions (e.g. rate of interest, emi amount, frequency of emi payment etc.) for a loan account are summarized and captured for each loan account.

Observation:
54 customers have high outstanding principal, have interest to be paid and we also see that their loan to value ratio is higher. Hence, there is high probability that these customers may default in future

Conclusion
With help of PCA we have been able to reduce 33 numeric features into 8 components which is able to explain 82% of variance in the data

With help of reduced components we have been able to observe some patterns. Using some rules around business context we are able to shortlist few customers who need to be monitored closely either for advance closure (28 out of 2319) or for possible default case (54 out of 2319).

Using the components additional rules can be derived and analyzed.

Unsupervised learning like clustering can further be applied on the data to segment the customers based on the components created and further analyzed.
