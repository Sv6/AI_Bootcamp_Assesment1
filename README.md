# AI_Bootcamp_Assesment1

### Problem Statement:

Dream Housing Finance, a company specializing in home loans, operates in urban, semi-urban, and rural regions.

When a customer applies for a home loan, the company verifies their eligibility before approving the loan.

The company aims to automate the loan eligibility assessment process in real-time based on customer details provided during the online application. These details include factors such as Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History, among others. The goal is to use this data to segment customers and identify those eligible for a loan, allowing the company to focus its efforts on targeting these specific customers. A partial dataset has been provided for this purpose.


### Dataset Key Information.
| Key Name           | Description                                 |
|--------------------|---------------------------------------------|
| Loan_ID            | Unique Loan ID                              |
| Gender             | Male/ Female                                |
| Married            | Applicant married (Y/N)                     |
| Dependents         | Number of dependents                        |
| Education          | Applicant Education (Graduate/ Under Graduate) |
| Self_Employed      | Self-employed (Y/N)                         |
| ApplicantIncome    | Applicant income                            |
| CoapplicantIncome  | Coapplicant income                          |
| LoanAmount         | Loan amount in thousands                    |
| Loan_Amount_Term   | Term of a loan in months                    |
| Credit_History     | Credit history meets guidelines             |
| Property_Area      | Urban/ Semi-Urban/ Rural                    |
| Loan_Status        | Loan approved (Y/N) **Target**                       |

### You are required to:
- **Clean** the data if necessary.
- all preprocessing steps **should be** in the notebook.
- Test **3 different classification models**.
- Perform **hyperparameter tuning** (Example: Grid Search or Random Search) & Cross Validation on the **best-performing model** from the **3 tested**.
- **Save** the final model (for example: pickle).
- The **submission** should include your Notebook, Model, and any other relevant files.

Good luck.
