

# Bank_Loan
Predictive analytics for Bank Loan.

# Introduction
In the realm of the financial sector, financial institutions such as banks meticulously analyze the creditworthiness of potential borrowers before disbursing loans or extending credit lines. This meticulous assessment is essential to gauge the level of risk associated with lending capital. It serves as a critical decision-making tool, aiding lenders in determining whether to grant the requested loan, specifying the appropriate interest rate, and outlining the terms of the lending arrangement.

One of the primary challenges faced in this process is the identification of individuals who may pose a higher likelihood of defaulting on their debt obligations. Mitigating this risk is paramount to maintain a robust and profitable lending portfolio. Hence, the establishment of a well-defined set of guidelines or a comprehensive system designed to assess borrowers rigorously and subsequently reduce financial exposure is of great strategic importance. Such a framework would not only enhance the lender's ability to make prudent lending decisions but also contribute significantly to the overall risk management and sustainability of the institution's financial health.

# Objective of this case study
The primary objective of this project from SCTP is to develop a predictive model with a certain degree of accuracy for the purpose of classifying borrowers into two distinct categories: those who default on their loans and those who do not (non defaulter). This classification process will rely on an extensive array of financial variables or called catergorical feature which show on the first table on the right hand column, ensuring a comprehensive and robust assessment of borrower behavior.

To accomplish this task, five AI modeling techniques are adopted to provide an in-depth study, targeting to improve the bank’s loaning processes. Through analyzing customers’ data sets and combining machine-learning algorithms, the conclusive findings have been encapsulated in the Conclusion section at the last paragraph. For individuals seeking a deeper exploration of the machine-learning code used in this study, we invite you to visit our GitHub repository, where you can access and download the code. Additionally, on the right-hand side of this website, we have included succinctly presented visual diagrams to facilitate a clearer comprehension of the project's key aspects.

# Conclusion
The features within the dataset play a crucial role in predicting the target variable. An examination of the correlation coefficient chart reveals an overall weak correlation among these features. Specifically, we observe that Interest rate, employment type, and gender are correlated with the Default status to some extent. This finding suggests that the predictive model's ultimate performance is likely to be constrained, as the presence of weak correlations indicates that achieving a high degree of accuracy may be challenging.

When looking at overall accuracy of both models, Logistic Regression and Random Forest, stands at 80%. Even after thorough hyperparameter tuning, the models have been unable to achieve an accuracy of 90% or higher. This limitation is primarily attributed to the inherent complexity of the data, which is compounded by noise that adversely impacts accuracy. Furthermore, the process of feature selection may have introduced inaccuracies by retaining irrelevant variables or excluding crucial ones, ultimately resulting in suboptimal predictive performance.

As a recommended course of action to enhance the model's effectiveness, propose improvements in data quality is the pathforward. This can be achieved by augmenting the dataset with additional relevant features. Specifically, incorporating measures such as Credit History, a more detailed breakdown of Income levels categorized into five levels, capturing information related to employment stability (e.g., tenure at their current company), evaluating Debt-to-Income ratios, and considering the age of the borrower will significantly contribute to refining the model's predictive capabilities. These enhancements will provide a more comprehensive and accurate representation of borrower profiles, ultimately leading to improved predictive accuracy in loan assessment.

