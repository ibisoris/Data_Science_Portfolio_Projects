# Loan Prediction Analysis

## Dataset Information
Dream House Finance company deals in all home loans. They have presence across all urban and rural areas. Customer first apply for home loan after the company validates the customer eligibility for loan. Company wants to automate the loan eligibility process(real time) based on customer details provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependants,Income, Loan Amount, Credit History and Others. To automate this process,They have given a process to identify the customers segments, those are eligible for loan amount so that they can specifically target these customers.

This is a standard supervised classification task. A classification problem where we have to predict whether a loan would be approved or not. Below is the dataset attributes.

## Attributes 
            Variable                   Description
    -------------------------------------------------------------
           Loan_ID                    unique Loan ID
           Gender                     Male/Female
           Married                    Married(Y/N)
           Dependents                 Number of Dependents
           Education                  Graduate/Undergraduate
           Self_Employed              self employed(Y/N)
           ApplicandIncome            applicant income
           Coapplicantincome          Coapplicant Income
           LoanAmount                Loan amount in thousand
           Loan_Amount_Term          Term of loan in months
           Credit_History            Credit history meets guidelines
           Property_Area             Urban/Semi Urban/Rural
           Loan_Status               Loan approved(Y/N)

## Modules Imported

import pandas as pd
import numpy as np
import seaborn as sns
from matplotlib import pyplot as plt
import matplotlib
%matplotlib inline

## Basic Statistics

	ApplicantIncome	CoapplicantIncome	LoanAmount	Loan_Amount_Term	Credit_History
count	614.000000	614.000000	592.000000	600.00000	564.000000
mean	5403.459283	1621.245798	146.412162	342.00000	0.842199
std	6109.041673	2926.248369	85.587325	65.12041	0.364878
min	150.000000	0.000000	9.000000	12.00000	0.000000
25%	2877.500000	0.000000	100.000000	360.00000	1.000000
50%	3812.500000	1188.500000	128.000000	360.00000	1.000000
75%	5795.000000	2297.250000	168.000000	360.00000	1.000000
max	81000.000000	41667.000000	700.000000	480.00000	1.000000


