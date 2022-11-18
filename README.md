Cryptocurrencies

We used Unsupervised Machine Learning techniques to analyze cryptocurrency data.

Project Overview



This project uses machine learning to identify which cryptocurrencies are on the trading market and to better understand how cryptocurrencies should be grouped to create classifications for developing an investment product. Unsupervised machine learning was chosen used since there is no known output for "what I'm looking for". To group the cryptocurrencies. Clustering algorithm was also chosen to help determine whether or not I should be investing in this product.

Steps followed during  this project:

* Data preprocessing. This step included in-depth data cleaning, such as removing null values and removing cryptocurrencies without coins mined. In addition, the encoding method "get_dummies()" was used for the text features and StandardScaler() was used to standardize and transform the data.

* Reducing data dimensions using PCA. In this step, a Dataframe's dimensions was reduced to three principal components and a new dataframe was created.

* Clustering cryptocurrencies using K-means. During step, an elbow curve was created to find the best value for the clustering groups and a K-means algorithm was used to predict the K clusters for the cryptocurrencies’s data.


* Visualizing results. In this final step, we used: a 3D scatter plot to visualize the three PCAs.

Figure 1:

![image](https://user-images.githubusercontent.com/101227930/184193382-a08bde91-1150-4a30-a4ae-40f609034fdb.png)



Conclusions


Bitcoin is in a class by itself. This is obvious in both the three dimensional cluster modeling and the scatterplot. This is obviously useful as Bitcoin can be studied as an exemplar.
It would be very instrumental to run this analysis again without the Bitcoin data, so see if the elbow curve finds a different optimal cluster value and so that we can see the distribution of the data better in the 3D Plot. 
We can use these findings to compare all cryptocurrencies against Bitcoin, and to re-run the unsupervised machine learning without Bitcoin to more fully understand the rest of the cryptocurrency market.





Contact:

email: ehawkins0631@gmail.com

twitter: @evahawkins3006

Linkedin https://www.linkedin.com/in/eva-hawkins-a9b333147/
