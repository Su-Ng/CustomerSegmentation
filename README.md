

Customer Segmentation is an interesting data science application. I will be using it to analyse the age, income, gender of the people shopping in the mall. In addition I will be using machine learning techniques to help to come up with a better strategy to market the products to the right segment of the shoppers in the mall.

![Alt text](RplotGender.png?raw=true "Title")

The above visualization shows that there is a higher number of females than males in the mall. 


![Alt text](RplotAge.png?raw=true "Title")

The above visualization shows that the maximum age group is 30 to 35. 

![Alt text](RplotBoxplotAge.png?raw=true "Title")

The above visualization shows the minimum age is 18 and the maximum age is 70.

![Alt text](RplotHistogramIncome.png?raw=true "Title")

In the kernal density plot we displayed, the annual income has a normal distribution.

![Alt text](RplotSpendingScore.png?raw=true "Title")

THe minimum Spending Score is 1 and maximum Spending Score is 99. The average Spending Score is 50.2. From the histogram, class 40 and 50 has the highest spending score.




This idea to do this is to gain insights into what are the demographics of the people shopping in the mall. I want to find out who are the highest spenders in the mall. With this knowledge and insight, we can target the right consumers who are most likely to spend.

Using machine learning algorithm, k nearest neighbour kNN, I aim to find clusters showing particular income group spending more, as well as a particular age group spending more. This can help the mall tenants understand how to increase their sales by selling more products catered to this income group and age group

![Alt text](RplotISS.png?raw=true "Title")

K means algorithm calculates the clustering algorithm for several values of K. We then calculate the total intra cluster sum of squares (ISS). We plot ISS based on the number of k clusters. The bend or elbow of the plot indicates the optimal number of clusters.

![Alt text](RplotKnn6.png?raw=true "Title")

From the visualization we observe 5 clusters. 
Cluster 3 and 4 have medium income and medium spending.
Cluster 1 have low income, high spending.   
Cluster 2 have low income, low spending.
Cluster 5 have high income, low spending.
Cluster 6 have high income, high spending.

We can target the high income and high spending people shopping in the mall to buy more.


![Alt text](RplotAgeClustering.png?raw=true "Title")

From the visualization we observe 6 clusters.
Cluster 1 and Cluster 6 are young and high spending customers. We should target this group of shoppers in the mall, get more products that appeal to younger age group shoppers.
