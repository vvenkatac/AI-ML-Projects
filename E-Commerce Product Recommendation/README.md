<h1> Recommendation Systems </h1>
<h2> Context:</h2>
Online E-commerce websites like Amazon, Flipkart uses different recommendation models to provide different suggestions to different users. Amazon currently uses item-to-item collaborative filtering, which scales to massive data sets and produces high-quality recommendations in real-time.
<br>
<h2> Domain: </h2>
E-commerce
<br>
<h2> Data Description </h2>
Amazon Reviews data (data source). The repository has several datasets. For this case study, we are using the Electronics dataset.
<br>
<h2> Attribute Information </h2>
● userId : Every user identified with a unique id <br>
● productId : Every product identified with a unique id <br>
● Rating : Rating of the corresponding product by the corresponding user <br>
● timestamp : Time of the rating ( ignore this column for this exercise) 
<br>
<h2> Objective </h2>
Build a recommendation system to recommend products to customers based on the their previous ratings for other products. <br>
● Exploratory Data Analysis <br>
● Creating a Recommendation system using real data <br>
● Collaborative filtering 
<br>
<h2> Project Steps </h2> 
1. Read and explore the given dataset. (Rename column/add headers, plot histograms, find data characteristics) <br>
2. Take a subset of the dataset to make it less sparse/ denser. ( For example, keep the users only who has given 50 or more number of ratings )  <br>
3. Split the data randomly into train and test dataset. ( For example, split it in 70/30 ratio)  <br>
4. Build Popularity Recommender model.  <br>
5. Build Collaborative Filtering model.  <br>
6. Evaluate both the models. ( Once the model is trained on the training data, it can be used to compute the error (RMSE) on predictions made on the test data.)  <br>
7. Get top - K ( K = 5) recommendations. Since our goal is to recommend new products for each user based on his/her habits, we will recommend 5 new products.  <br>
8. Summarise your insights. 
