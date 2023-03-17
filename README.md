# Walmart Sales Prediction
This project is a part of the Post Graduate Program Certification Course in Data Science Engineering at [GreatLearning Institute](https://www.mygreatlearning.com/).

#### -- Project Status: [Completed]

## Project Introduction/Objective:
Conventional retail stores still play a prominent role in a world dominated by Ecommerce. As time has passed, retailers have had to evolve in order to keep up with changes in demands and the ever-changing mindset of customers. One such retail industry juggernaut that has kept up with the demands of customers as well changed the face of the retail industry for the better is Walmart Inc. We are trying to build a model to improve the sales of the organization as well as better service for the customers.

### Methods Used
* Inferential Statistics
* Machine Learning
* Data Visualization
* Predictive Modeling

### Technologies
* Python
* Pandas, NumPy, Scikit-Learn, Matplotlib, seaborn
* statsmodels.api
* Jupyter


## Needs of this project

- data exploration/descriptive statistics
- Data Visualization
- data processing/cleaning
- Feature Engineering
- Statistical Analysis
- statistical modeling
- Machine Learning (Supervised)
- Literature Survey
- Reporting
- Presentation

## Getting Started

### Dataset and Domain 
This dataset was downloaded from the Kaggle platform which has three years weekly sales data and under the domain of Marketing Analysis.

### Data Dictionary and Variable Categorization 
The data sources for the project have been downloaded from Kaggle and was used in Competitions hosted on Kaggle.

The datasets consist of historic data of weekly sales for different stores of Walmart. There are 400000+ records classified into different stores, departments, size and has markdowns (promotions).
Below table lists the number of features that is available for this dataset. We can classify the features based on the datatype or their behaviour. We can broadly classify the features as either numeric or categorical. 
**Quantitative variables** are any variables where the data represent amounts (e.g., weekly sales, weight, or age). These are broadly called as numerical variables or features. 
Categorical variables are any variables where the data represent groups. This includes rankings (e.g., finishing places in a race), classifications (e.g., brands of cereal), and binary outcomes (e.g., coin flips).

### Data Dictionary and Pre-processing Data Analysis

|S.No |Variables Names| Categorization of Variable| Null values Check|
|-----|---------------|---------------------------|------------------|
|1.| Store| Numeric| 421570 non_null int 64|
|2.| Dept| Numeric| 421570 non_null int 64|
|3.| Date| Discrete(Numeric)| 421570 non_null datetime64|
|4.| Weekly_Sales| Numeric| 421570 non_null float64|
|5.| IsHoliday| Binary(Categorical)| 421570 non_null bool|
|6.| Type| Categorical| 421570 non_null object|
|7.| Size| Numeric| 421570 non_null int 64|
|8.| Temperature| Continuous (Numeric)| 421570 non_null float|
|9.| Fuel_Price| Continuous (Numeric)| 421570 non_null float|
|10.| MarkDown1| Numeric| 150681 non_null float|
|11.| MarkDown2| Numeric| 111248 non_null float|
|12.| MarkDown3| Numeric| 137091 non_null float|
|13.| MarkDown4| Numeric| 134967 non_null float|
|14.| MarkDown5| Numeric| 151432 non_null float|
|15.| CPI| Continuous (Numeric) 421570 non_null float|
|16.| Unemployment| Continuous (Numeric) 421570 non_null float|

### Attribute information
|Feature|Type|Description|
|-------|-----|------------|
|Store|Numeric|Store details with Unique identifier -Number was given to each 45 stores.|
|Dept|Numeric|Department detail with Unique identifier was given to each 81 departments.|
Date|Discrete(Numeric)|Given every Friday date of the week .Date is between 05/02/2010 and 22/10/2010. The format of the date is in YYYY-MM-DD. There is a weak difference in each record.|
|Weekly_Sales|Numeric|Sales per week at a given store.|
|IsHoliday|Binary(Categorical)|Given every Friday date of the week. Holidays in a week are given in True or False, This is the data where a weekday is a holiday or not in the week. If weekday is a holiday it is True or it is False.|
|Type|Categorical|A, B, C are the type of Walmart stores given. Considering the description we are taking these stores as Hypermarkets, Discount department Stores, Grocery 
Stores.|
|Size|Numeric|Size of the store is given.|
|Temperature|Continuous (Numeric)|Average temperature in the region (in ℉) where the store is located.|
|Fuel_Price|Continuous (Numeric)|Cost of fuel in the region.|
|MarkDown1|Numeric|Promotion activities to boost sales on a special Holiday, Markdown are the discounts given in a particular store in a given date.|
|MarkDown2|Numeric|Promotion activities to boost sales on a special Holiday, Markdown are the discounts given in a particular store in a given date.|
|MarkDown3|Numeric|Promotion activities to boost sales on a special Holiday, Markdown are the discounts given in a particular store in a given date.|
|MarkDown4|Numeric|Promotion activities to boost sales on a special Holiday, Markdown are the discounts given in a particular store in a given date.|
|MarkDown5|Numeric|Promotion activities to boost sales on a special Holiday, Markdown are the discounts given in a particular store in a given date.|
|CPI|Continuous (Numeric)|The Consumer Price Index (CPI) measures the change in prices paid by consumers for goods and services. It indicates the changes in the value at present to the base value.|
|Unemployment|Continuous (Numeric)|Unemployment rate of the customers that visit the store.|

2. Raw Data is being kept [here](https://github.com/meastanmay/Walmart-Sales-Prediction) within this repo.
    
3. Data processing/transformation scripts are being kept [here](https://github.com/meastanmay/Walmart-Sales-Prediction/blob/main/EDA_Walmart_Sales_Prediction.ipynb)


## Featured Notebooks/Analysis/Deliverables
The project comprises of a set of 3 notebooks. Follow the order of Notebooks below to get along with the project code:
* [Exploratory Data Analysis and Feature Engineering](https://github.com/meastanmay/Walmart-Sales-Prediction/blob/main/EDA_Walmart_Sales_Prediction.ipynb)
* [Machine Learning Model Trained on Data without outliers](https://github.com/meastanmay/Walmart-Sales-Prediction/blob/main/Model_without_outliers.ipynb)
* [Machine Learning Model Trained on Data with outliers](https://github.com/meastanmay/Walmart-Sales-Prediction/blob/main/Model_with_outliers.ipynb)


## Contributing Project Team Members

**Team Leads (Contacts) : [Tanmay Agarwal](https://github.com/[meastanmay])**

#### Other Members:

|Name     | 
|---------|
|Bala Murli Krishna Vaka| 
|Vaishnavi Ravi |
|[Shubhash AVT](https://www.linkedin.com/in/shubhashavt/)|
|[Saurabh Valde](https://www.linkedin.com/in/saurabh-walde-693a2119a/)|

## Contact
* Feel free to contact team leads with any questions or if you are interested in contributing!
