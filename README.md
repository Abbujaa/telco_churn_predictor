Business Problem:
In the telecommunications industry, where customers have the flexibility to choose from multiple service providers and frequently switch between them, an annual churn rate averaging between 15% to 25% is the norm. It's worth noting that the cost of acquiring a new customer is notably higher, often 5 to 10 times more, compared to retaining an existing one. Consequently, customer retention has assumed a position of greater significance than customer acquisition.
For many incumbent operators in the telecom sector, the primary business objective is retaining high-profit customers.
To combat customer churn effectively, telecom companies must focus on predicting which customers are at a high risk of churning.

Motivation Behind Finding Solution:

Predicting customer churn is critical for telecommunication companies to be able to effectively retain customers. It is more costly to acquire new customers than to retain existing ones. For this reason, large telecommunications corporations are seeking to develop models to predict which customers are more likely to change and take actions accordingly.

Within the dynamic landscape of the telecommunications sector, customers wield the power to select from a multitude of service providers and seamlessly transition between them. This fiercely competitive market witnesses an annual churn rate that hovers between 15% and 25%. It's crucial to recognize that the expense associated with procuring a new customer significantly outweighs that of preserving an existing one, often by a factor of 5 to 10. As a result, the emphasis on customer retention has surged in prominence, surpassing the traditional focus on customer acquisition.

For many established players in the telecom industry, the paramount business objective now revolves around preserving their most lucrative customer base.

Input :
Customer Tenure (in months)
Phone Service: (No) or  (Yes)
Contract Type:  (Month-to-month),  (One year),  (Two years)
Paperless Billing:  (No) or  (Yes)
Payment Method:  (Bank transfer - automatic),  (Credit card - automatic), (Electronic check),  (Mailed check)
Monthly Charges ($)

Output
The application will present the following messages:
"The customer is expected to churn." or "The customer is not expected to churn."
"The probability of churn is: (X, Y)."

About the Dataset:
The data set used in this article is available in the Kaggle (CC BY-NC-ND) and contains nineteen columns (independent variables) that indicate the characteristics of the clients of a fictional telecommunications corporation. The   “Churn” column (response variable) indicates whether the customer departed within the last month or not. The class “No” includes the clients that did not leave the company last month, while the class “YES” contains the clients that decided to terminate their relations with the company. The objective of the analysis is to obtain the relation between the customer’s characteristics and the churn.

https://www.kaggle.com/datasets/blastchar/telco-customer-churn

Requirements :
streamlit
pandas
picke-mixin

