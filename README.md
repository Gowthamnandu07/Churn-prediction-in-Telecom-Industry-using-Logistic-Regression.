### Dear Hiring Team,

I am thrilled to showcase my passion for my work by creating this README file. This document serves as a comprehensive guide about my project, providing answers to any queries you may have about the project source code. As you review this file, you will find it to be a one-stop resource for all your end-to-end queries about the project deployment.

I am confident that my dedication to delivering high-quality work and my attention to detail will be evident to you as you review this document. Thank you for your time and consideration, and I look forward to discussing my project with you in greater detail.

Sincerely,
[Gowtham Nandu]





                                        Telecom Customer Churn Prediction

![customer churn](https://github.com/Gowthamnandu07/Churn-prediction-in-Telecom-Industry-using-Logistic-Regression./assets/118471519/6f88dff0-2238-4f0c-8b35-f9ecea26784f)

### What is Customer Churn?
When customers or subscribers end their business with a firm or service, it's referred to as customer churn. 

In the telecom industry, customers have various service providers to choose from and frequently switch between them. Due to this competition, the telecommunications industry has an annual churn rate of 15-25 %. However, personalized customer retention is difficult for most firms, as they have a large customer base and cannot devote much time to each individual. The costs of doing so would outweigh the additional revenue. Nonetheless, if a company could predict which customers were most likely to leave, they could focus their retention efforts on these "high risk" clients, ultimately expanding their coverage area and increasing customer loyalty. 


The key to succeeding in this market is the customer themselves. Customer churn is a crucial metric because it's more cost-effective to retain existing customers than to acquire new ones. To detect early signs of potential churn, firms must first develop a comprehensive understanding of their customers and their interactions across various channels. By addressing churn, businesses can not only preserve their market position but also grow and thrive. The more customers in their network, the lower the cost of initiation and the larger the profit. Therefore, the company's primary focus for success should be reducing client attrition and implementing effective retention strategies.


### Objectives:
➔ Discovering the optimal machine learning model for accurately distinguishing between Churn and non-Churn customers.

➔ Examining the information based on different attributes that contribute to the departure of customers.

➔ Determining the percentage of customers who churn and those who continue to use active services. 

  
 ### Dataset:
[Telco customer churn🙂](https://www.kaggle.com/bhartiprasad17/customer-churn-prediction/data)

## The data set includes information about:
➔ The column labeled Churn contains information about customers who have departed within the past month.

➔ Information regarding the demographics of customers, including their gender, age group, and whether they have partners or dependents.

➔ The services that every client has subscribed to include phone, various lines, internet, online security, online backup, device safeguarding, technical assistance, and      streaming of television shows and films.

➔ Details regarding customer accounts include their tenure as a customer, contract status, payment mode, preference for paperless billing, monthly expenses, and overall        charges.

### Implementation:
Libraries: sklearn, Matplotlib, pandas, seaborn, and NumPy

### Few glimpses of EDA:

## 1. Churn distribution:
![Churn Distribution](https://github.com/Gowthamnandu07/Churn-prediction-in-Telecom-Industry-using-Logistic-Regression./assets/118471519/650c3a97-bd3b-4c90-8116-bc6cb6b9ffea)    A Total of 26.6% of customers moved to a different company.

## Distribution of churn based on gender:
![distributionWRTGender](https://github.com/Gowthamnandu07/Churn-prediction-in-Telecom-Industry-using-Logistic-Regression./assets/118471519/3f2acf07-0a11-4044-9cf9-a40738f698ae)  
The percentage/count of customers who switched service providers was almost identical for both genders. Both males and females exhibited similar behavior when it came to transitioning to a different service provider/company.

## 3. Customer Contract distribution:
![Contract distribution](https://github.com/Gowthamnandu07/Churn-prediction-in-Telecom-Industry-using-Logistic-Regression./assets/118471519/e2385474-7e30-4b51-a411-d226110e6114) 
                 Out of the customers who had a Month-to-Month Contract, 75% decided to leave, while only 13% of those with a One Year Contract and 3% with a Two Year Contract chose to do so.

## 4. Payment Methods:
![payment methods](https://github.com/Gowthamnandu07/Churn-prediction-in-Telecom-Industry-using-Logistic-Regression./assets/118471519/0b0ede76-a93b-4f44-8844-cb876294a540)
![payment ethods with respectto churn](https://github.com/Gowthamnandu07/Churn-prediction-in-Telecom-Industry-using-Logistic-Regression./assets/118471519/f8b45b17-5d11-44ca-8738-3912e2971f6b) 
The customers who discontinued their services primarily used Electronic Check as their payment method. However, those who chose Credit-Card automatic transfer, Bank Automatic Transfer, or Mailed Check as their payment method were more likely to remain as customers.

## 5. Internet services:
![internet services](https://github.com/Gowthamnandu07/Churn-prediction-in-Telecom-Industry-using-Logistic-Regression./assets/118471519/e76dc7fe-3f5d-46a8-ac16-e574fd5adb7d) 
The Fiber optic service is favored by many customers, but it appears that those who use it tend to have a higher churn rate, which could indicate dissatisfaction with this type of internet service. On the other hand, the majority of customers use DSL service and experience a lower churn rate in comparison to Fiber optic service.

## 6. Dependent distribution:
![Telecom_Churn_Prediction-e1587281300645](https://github.com/Gowthamnandu07/Churn-prediction-in-Telecom-Industry-using-Logistic-Regression./assets/118471519/939cea37-4ac7-4432-ad10-65d3d97b08d3)
There is a higher probability of customers churning if they do not have any dependents.

## 7. Online Security:
![onlineSecurity](https://github.com/Gowthamnandu07/Churn-prediction-in-Telecom-Industry-using-Logistic-Regression./assets/118471519/89c209fd-cd96-491c-990e-2e7a3c921d1a)
The graph below illustrates that the majority of customers churn because of inadequate online security measures.

## 8. Senior Citizen:
![seniorCitzen](https://github.com/Gowthamnandu07/Churn-prediction-in-Telecom-Industry-using-Logistic-Regression./assets/118471519/37b0b162-feaa-4fd5-b60e-331366c20e20)
The majority of senior citizens tend to leave, as they make up a small proportion of the overall customer base.

## 9. Paperless Billing:
![seniorCitzen](https://github.com/Gowthamnandu07/Churn-prediction-in-Telecom-Industry-using-Logistic-Regression./assets/118471519/1427406d-332d-4cd5-8dbe-7a2d291471ab)
The probability of customers churning is higher for those who opt for Paperless Billing.

## 10. Tech support:
![techSupport](https://github.com/Gowthamnandu07/Churn-prediction-in-Telecom-Industry-using-Logistic-Regression./assets/118471519/19ba6543-d499-41b9-9933-0bca52697ba9)
As shown in following chart, customers with no TechSupport are most likely to migrate to another service provider.

## 11. Distribution w.r.t Charges and Tenure:
![carges distribution](https://github.com/Gowthamnandu07/Churn-prediction-in-Telecom-Industry-using-Logistic-Regression./assets/118471519/1aa2ed51-0ccf-4440-885a-bbde8f716ed8)
![total charges](https://github.com/Gowthamnandu07/Churn-prediction-in-Telecom-Industry-using-Logistic-Regression./assets/118471519/4c47c95f-fb54-4956-911d-33e4889d2a16)
![tenure and churn](https://github.com/Gowthamnandu07/Churn-prediction-in-Telecom-Industry-using-Logistic-Regression./assets/118471519/0e91e7ec-8d97-4591-bca1-15e89e9eff20)
Customers with higher Monthly Charges are also more likely to churn.
New customers are more likely to churn.

## Machine Learning Model Evaluations and Predictions:
# 1. Linear Regression:
![56ffed24-7ff9-4500-84ff-b891fe9e1440](https://github.com/Gowthamnandu07/Churn-prediction-in-Telecom-Industry-using-Logistic-Regression./assets/118471519/531c332f-90d4-487e-980a-587e033c73d8)

# 2. Random Forest:
![dd817a95-f5c4-43be-b762-a447c14c28b4](https://github.com/Gowthamnandu07/Churn-prediction-in-Telecom-Industry-using-Logistic-Regression./assets/118471519/5668fc2d-0209-45f4-a512-885ead134101)

# 3. SVM:
![57eb8b14-f2c7-4d82-80ca-c8ad8870272c](https://github.com/Gowthamnandu07/Churn-prediction-in-Telecom-Industry-using-Logistic-Regression./assets/118471519/0fd33c4a-8129-4e46-aea6-e36f94f1c392)





### Optimisers:
We can use Hyperparameter tuning and Cross-validation ethods to improve the accuracy further.

### Feedback:
If you have any feedback, please reach out at {vgnunique@gmail.com}

## 🚀 About Me
Hi, I'm Gowtham! 👋
I am Data science Enthusiast and ML practitioner.


😉








