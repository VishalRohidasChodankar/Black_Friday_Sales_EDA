# Black_Friday_Sales_EDA

### About Dataset

- Dataset History

A retail company “ABC Private Limited” wants to understand the customer purchase behavior (specifically, purchase amount) against various products of different categories. They have shared purchase summaries of various customers for selected high-volume products from last month.
The data set also contains customer demographics (age, gender, marital status, citytype, stayincurrentcity), product details (productid and product category) and Total purchaseamount from last month.

Now, they want to build a model to predict the purchase amount of customers against various products which will help them to create personalized offers for customers against different products.

### Data Source

- Kaggle [Download File](https://www.kaggle.com/datasets/pranavuikey/black-friday-sales-eda/download?datasetVersionNumber=1)

### Tools

- Excel
- Pythons [View File](https://www.kaggle.com/code/vishalchodankar/black-friday-sales-eda-vishal)

### Tasks to perform

- Purchase column is the Target Variable, perform Univariate Analysis and Bivariate Analysis w.r.t the Purchase.

- Masked in the column description means already converted from categorical value to numerical column.

- Below mentioned points are just given to get you started with the dataset, not mandatory to follow the same sequence.

### DATA PREPROCESSING

- Check basic statistics of dataset

- Check for missing values in the data

- check for unique values in data

- Perform EDA

- Purchase Distribution

- check for outliers

- Analysis by Gender, Marital Status, occupation, occupation vs purchase , purchase by city, purchase by age group, etc

- Drop unnecessary fields

- Convert categorical data into integer using map function (e.g 'Gender' column)

- missing value treatment

- Rename columns

- fill nan values

- map range variables into integers (e.g 'Age' column)


### Data Visualisation

visualize individual column
Age vs Purchased
Occupation vs Purchased
Product_category_1 vs Purchased
Product_category_2 vs Purchased
Product_category_3 vs Purchased
City category pie chart
check for more possible plots

### Leaning 

In the Given dataset. I explored and learned many things like, How to fill NaN values. Where we can use the concept of code reusability. In the process of cleaning the dataset, I used Pandas and Numpy libraries. Using pandas and numpy I removed unwanted(useless) data created new data frames and got useful data for my research. After cleaning my data I used Seaborn and Matplotlib libraries to read my data by visualizing it. I created questions regarding my research I tried to solve them by visualizing and applying conditions. Now, they want to build a model to predict the purchase amount of customers against various products which will help them to create personalized offers for customers against different products. By seeing this EDA we can fulfill this requirement.




