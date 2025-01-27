# Overview
The rising number of loan applications around the world is putting a lot of pressure
on banks to process and approve loans quickly and accurately. Unfortunately, this
often leads to delays and inconsistencies, making it harder for banks to properly
assess applicants. This also causes the employees at the bank to be under so much
stress and always occupied which in result causes the banks to be always crowded
all the time.


To solve this, we’ve developed a machine learning model that predicts the chances
of a loan being approved based on different factors. This model helps banks speed
up their approval process, make better decisions, and lower the risk of defaults.


This is achieved by firstly exploring the dataset of some loan applicants in a bank.
Data preprocessing is then applied to remove several outliers in the data, to fill in
the records with no data in some parts, and to encode categorical data to convert it
to numerical form. 


The last part is to build several machine learning models and a
final evaluation is utilized to select the best model based on performance. 5 models
were utilized during this process: Logistic regression, K- Nearest Neighbours,
Support Vector Machine, Decision Tree and Random Forest.

# About the Dataset
The dataset contains 58644 row, and 13 columns. Below is an overview of the features found in the dataset.
ID
- person_age
- person_income (annual income)
- person_home_ownership:
  - Own: which means the person owns the house
  - Rent: which means the person is paying rent for living in the house
  - Mortgage: which means the person is taking a loan to own the house
- person_emp_length: which means the duration of employment in months
- loan_intent: which means the reason for applying for a loan
- loan_grade: The bank has several grades from A to G (we will discuss this point in detail)
- loan_amnt: amount of loan needed
- loan_int_rate: interest rate for the loan decided by the bank
- loan_percent_income: the percentage of the loan compared to the income of the person
- cb_person_default_on_file: This field declares if the person has paid all his credit debt or not (N means he has fully paid, and Y means he didn’t).
- cb_person_cred_hist_length: Credit history of the applicant in months.
- loan_status: declares whether the loan is approved or not.

# Tools
- Python --> 3.12
- Numpy --> 2.2.2
- Pandas --> 2.2.3
- seaborn --> 0.13.2
- matplotlib --> 3.10.0
- scikit learn --> 1.6.1
