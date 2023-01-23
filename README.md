# CLTV-prediction-of-an-Insurance-Company

**PROBLEM STATEMENT:**

We have to predict Customer Life Time Value of customers of VahanBima company. The target variable is a continuous numerical variable. So the task is building a  ‘Regression Model’.

**Dataset Description:**

The give data contains two data sets i.e.., training data set and test data set. The shape of train data set is (89392, 12). The shape od test data set is (59595, 11)

**Features:**
* Id is just noise that has no impact on cltv  (target variable)
* **Categorical columns:** gender, area, qualification, income, marital_status, num_policies, policy, type_of_policy 
* **Numerical columns:** vintage, claim_amount, cltv

**Exploratory Data Analysis:**
* The two datasets i.e.., train and test data sets are merged in to one data frame and data analysis is performed. Some of the important key takeaways are listed below.

**Univariate analysis:**


![image](https://user-images.githubusercontent.com/121590533/213989780-8fc598e8-96a5-43ac-a97d-eb2f33d455f7.png)
* From the distribution we can infer that CLTV is highly right skewed. 

![image](https://user-images.githubusercontent.com/121590533/213990008-b5b78d36-9ac5-4714-987b-8505cab018d8.png)

* From the box plot it is observed that there are lot of outliers in our dependent variable but we cant treat them directly because they are influential points.

**Evaluation Metrics:**

For the Given project requirement R^2 is used.

**SUPERVISED MODELS USED:**
   
   
