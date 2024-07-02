# EDA_2-adult_with_headers_Dataset-
About the Data:
CharityML is a fictitious charity/non-profit organization located in the heart of Silicon Valley that was established to provide financial support for people and it survives only on donations. After nearly 32,000 letters were sent to people in the community, CharityML determined that every donation they received came from someone that was making more than $50,000 annually. To expand their potential donor base, CharityML has decided to send letters to residents of California, but to only those most likely to donate to the charity. With nearly 15 million working Californians, CharityML has brought you on board to help build an algorithm to best identify potential donors and reduce overhead cost of sending mail.

Understanding an individual's income can help a non-profit better understand how large of a donation to request, or whether or not they should reach out to begin with. While it can be difficult to determine an individual's general income bracket directly from public sources, we can (as we will see) infer this value from other publically available features.

In this project, we will employ several Machine Learning algorithms of to accurately model individuals' income using data collected from the 1994 U.S. Census. The ultimate goal with this implementation is to construct a model that accurately predicts whether an individual makes more than $50,000.

The dataset for this project basically originates from the UCI Machine Learning Repository. (University of California, Irvine, School of Information and Computer Science, Center for Machine Learning and Intelligent Systems) The UCI Machine Learning Repository is a collection of databases, domain theories, and data generators that are used by the machine learning community for the empirical analysis of machine learning algorithms. The archive was created as an ftp archive in 1987 by David Aha and fellow graduate students at UC Irvine. Since that time, it has been widely used by students, educators, and researchers all over the world as a primary source of machine learning data sets.

Data Summary:
age: Numerical, representing the age of the individual.
workclass: Categorical, indicating the type of employment (e.g., State-gov, Private).
fnlwgt: Numerical, representing the final weight, which is a factor indicating the number of people the observation represents.
education: Categorical, indicating the highest level of education attained (e.g., Bachelors, HS-grad).
education_num: Numerical, representing the number of years of education.
marital_status: Categorical, indicating the marital status (e.g., Never-married, Married-civ-spouse).
occupation: Categorical, indicating the type of occupation (e.g., Adm-clerical, Exec-managerial).
relationship: Categorical, indicating the individual's relationship to the household (e.g., Not-in-family, Husband).
race: Categorical, indicating the race of the individual (e.g., White, Black).
sex: Categorical, indicating the gender of the individual (Male, Female).
capital_gain: Numerical, indicating capital gains.
capital_loss: Numerical, indicating capital losses.
hours_per_week: Numerical, representing the number of hours worked per week.
native_country: Categorical, indicating the native country of the individual.
income: Categorical, indicating whether the income is less than or equal to 50K or more than 50K.

Let's summarize this data with some statistics and insights.
Data Exploration and Preprocessing: 
• Load the dataset and conduct basic data exploration (summary statistics, missing values, data types).
• Handle missing values as per the best practices (imputation, removal, etc.). 
• Apply scaling techniques to numerical features: • Standard Scaling • Min-Max Scaling 
• Discuss the scenarios where each scaling technique is preferred and why.
Encoding Techniques: 
• Apply One-Hot Encoding to categorical variables with less than 5 categories. 
• Use Label Encoding for categorical variables with more than 5 categories. 
• Discuss the pros and cons of One-Hot Encoding and Label Encoding.
Feature Engineering: 
• Create at least 2 new features that could be beneficial for the model. Explain the rationale behind your choices. 
• Apply a transformation (e.g., log transformation) to at least one skewed numerical feature and justify your choice.
Feature Selection: 
• Use the Isolation Forest algorithm to identify and remove outliers. Discuss how outliers can affect model performance. 
• Apply the PPS (Predictive Power Score) to find and discuss the relationships between features. Compare its findings with the correlation matrix.
