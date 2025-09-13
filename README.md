# MFI_loan-repayment-predicting-model
📘 Project Overview
This project focuses on building a predictive model for loan repayment behavior in collaboration with a telecom provider and a microfinance institution (MFI). The goal is to enhance customer selection for mobile-based microcredit services targeted at low-income populations.

🎯 Problem Statement
Microfinance Institutions (MFIs) offer financial services to underserved communities, especially in remote areas. With the rise of mobile financial services (MFS), there's a push to deliver microloans more efficiently. However, adoption has been uneven, with both successes and challenges.
A telecom company, operating on a budget-friendly model, has partnered with an MFI to offer microcredit on mobile balances, repayable within 5 days. Customers who fail to repay within this window are considered defaulters. The repayment structure is simple:
- Loan of 5 IDR → Payback of 6 IDR
- Loan of 10 IDR → Payback of 12 IDR
The client seeks a data-driven solution to predict the likelihood of repayment for each loan transaction, helping them optimize credit allocation and reduce default risk.

🧠 Objective
Develop a machine learning model that predicts, with probability, whether a customer will repay their loan within 5 days.
- Label '1' → Loan repaid (Non-defaulter)
- Label '0' → Loan not repaid (Defaulter)

Key Tasks
- Data cleaning, exploration, and visualization
- Feature engineering and pattern discovery
- Model training using 45 different algorithms
- Hyperparameter tuning and metric selection
- Evaluation using metrics like Log Loss, Recall, and Precision
- Final report documenting methodology, insights, and results
