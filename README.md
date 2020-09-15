# Instacart-Market-Basket-Analysis

<h1>Bussiness Problem:</h1>
Instacart is a application which has its operation in US and Canada. We are given some csv files. Each csv file has unique information in it. Given all these data have to build a classification model. Which when given a product_id and order_id gives output as 0 or 1. Later we create dictionary with order_id as key and list of all products that are going to be reordered as the value of that key. Now this is the list of product which can be recommended.

<h1>Evaluation Metrics:</h1>
F1-Score

<h1>Data Provided</h1>
All files described below are csv files.

1 Aisles : aisle id and aisle name.

2 Department : Department Id, Department Name

3 Order_Products_prior : Order Id, Product Id, Add to cart product, Reorder

4 Order_Products_train : Order Id, Product Id, Add to cart product, Reordered

5 Orders : Order id, User id, Eval Set, Order Number, Order Day Of Week, Order Hour Of Day, Days Since Prior Order

6 Products : Product Id, Product Name, Aisle Id, Department Id

7 Sample Submission : Order Id, Products

<h1>Problem Specification</h1>

1. The aim of this problem is to build a classification model with good f1-score which can be used to recommend the products to the users.

2. The challenging task in this problem is its data size. There are around 13 crore rows in the Order_Products_prior so will have to any how find solution to work with this data.

3. Other challenge was understanding the data for train and test as the Order_Products_Prior and Order_Products_Train both has same columns and we have to any how fetch the train data after getting insights from prior data and getting required information through it.

<h1>My Approach</h1>

1. As Machine Learning is one of the fastest growing field. We almost see a new algorithm everyday. And till today there isn't a algorithm which can promise to work well in every condition.

2. Since there isn't any such algorithm I tried various classification algorithm. 

3. After seeing some top kernels I used some algorithms getting influenced from them. 

4. At the end I was able to create a satisfying F1-Score.

<h1>Repository Description</h1>
As I tried with various algorithm I wanted to keep everything in seperate files to make it look clear.

The repository contains files for EDA, Feature Engineering, Modelling and then a file which has function to predict a point at test time and evaluate metrics.

<h1>Winner's Approach And Sources I took Help with</h1>

<b>Source</b>Source:https://medium.com/kaggle-blog/instacart-market-basket-analysis-feda2700cded

In the blog 2nd Winner Kazuki Onodera describes his approach to the problem. Since I wanted to try my ways and make the project easy I didn't followed winners approach but just used it to gain some insights.

