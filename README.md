# LoanPrediction-2

## Event Details
- **Event Name** : Loan Prediction
- **Hosted by**  : Analytics Vidhya - Hackathon
- **Event Type** : Data Challenge

## Problem Statement
<p style="text-align: justify; font-family: 'Georgia', cursive, sans-serif; line-height: 1.5;">
Dream Housing Finance faced the challenge of efficiently validating customers eligibility for home loans. To address this, the company decided to automate the validation process in real-time using customer data such as gender, marital status, income, loan amount, and credit history.
</p>
<p style="text-align: justify; font-family: 'Georgia', cursive, sans-serif; line-height: 1.5;">
The project utilized the available datasets to develop machine learning models capable of identifying eligible customers. This solution not only improves operational efficiency but also enables the company to target customers more precisely.
</p>

## Varible Description
| Variable           | Description                               |
|--------------------|-------------------------------------------|
| Loan ID            | Unique Loan ID                            |
| Gender             | Male/ Female                              |
| Married            | Applicant married (Yes/ No)               |
| Dependents         | Number of dependents                      |
| Education          | Applicant Education (Graduate/ Not Graduate) |
| Self Employed      | Self employed (Yes/ No)                   |
| Applicant Income   | Applicant income                          |
| Coapplicant Income | Coapplicant income                        |
| Loan Amount        | Loan amount in thousands                  |
| Loan Amount Term   | Term of loan in months                    |
| Credit History     | Credit history meets guidelines           |
| Property Area      | Urban/ Semi Urban/ Rural                  |
| Loan Status        | (Target) Loan approved (Yes/ No)          |

## Model Development & Evaluation
<dl style="font-family: 'Georgia', serif; text-align: justify; line-height: 1.5;">
  <dt> Model: </dt>
  <dd> I used two machine learning models, which are Support Vector Machine (SVM) and Random Forest Classifier. </dd>
</dl>

<dl style="font-family: 'Georgia', serif; text-align: justify; line-height: 1.5;">
  <dt> Evaluation: </dt>
  <dd> I used F1-Score with the best parameters to assess the model performance. The results show that Random Forest is more responsive to optimization than SVM, with an F1-Score value of 85.87% after tuning. </dd>
</dl>

## Conclusion
