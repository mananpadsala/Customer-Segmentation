# ShopperInsights: Customer Segmentation
This project aims to segment customers based on their purchase behavior and demographics. The segmentation will allow for targeted marketing campaigns and personalized offers. Also, to anticipate the purchases that will be made by a new customer, during the following year and this, from its first purchase by assigning them appropriate cluster/segment

## Data
The data used in this project is a combination of purchase history and demographic information from an E-commerce database. Based on this analysis, We will predict segments for customers. The data includes information such as purchase history (CustomerID, products purchased, amount spent), and purchase information (InvoiceNo, StockCode,	Description,	Quantity,	InvoiceDate,	UnitPrice, Country).

## Methods
The segmentation will be performed using clustering algorithms, such as SVC, logistic Regression, K-Nearesr Neighbours, Decision Trees, Random Forest. The optimal number of clusters will be determined using techniques such as elbow method or silhouette analysis.

## Dependencies
* pandas
* NumPy
* scipy
* scikit-learn
* matplotlib
* seaborn
* nltk
* word cloud
* Jupyter notebook

## Install dependencies
```
Pandas:           $ sudo pip install pandas
NumPy:            $ sudo pip install numpy
scipy:            $ sudo pip install scipy
scikit-learn:     $ sudo pip install -U scikit-learn
matplotlib: 
                  $ sudo apt-get install libfreetype6-dev libpng-dev
                  $ sudo pip install matplotlib 
seaborn:          $ sudo pip install seaborn
jupyter notebook: $ sudo apt-get -y install ipython ipython-notebook
                  $ sudo -H pip install jupyter
nltk:              $ sudo pip install nltk
word cloud:         $ sudo pip install wordcloud
```

## Usage
* Dataset path: `./input_data/`
* Run the code given in ipython notebook `Cust_segmentation_online_retail.ipynb`

## Conclusion
The customer segmentation will enable the retail company to better understand their customers and create targeted marketing campaigns and personalized offers to increase sales and customer loyalty.

## Credit

~ Manan Padsala
