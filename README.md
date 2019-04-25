<h1> Sentimental Analysis of Amazon Baby Product Reviews </h1>
<p>
Sentimental Analysis is the process of computationally identifying and categorizing statements made from a piece of text and determine whether the author’s feelings toward a particular product is positive, negative or neutral. It is very vital for Industrial leaders like Amazon with their giant E-Commerce business to understand consumer behaviour and their sentiment to reach out better to them. With recent developments in the field of machine learning and text analytics this could be effectively achieved. In this project we aim to predict the sentiment or polarity of a review given to a particular amazon baby product using supervised machine learning algorithms. Based on that we will compare the performance of each of the approaches used and comment on the best approach for such applications.
</p>

<h2> Dataset [http://jmcauley.ucsd.edu/data/amazon/] </h2>
<p>
The Dataset used is from the official amazon product data hosted in the link above
and is provided by researchers from UCSD. This Review dataset contains the following features in
JSON format:
</p>
<ul>
  <li> reviewerID - ID of the reviewer, e.g. A2SUAM1J3GNN3B </li>
  <li> asin - ID of the product, e.g. 0000013714 </li>
  <li> reviewerName - name of the reviewer </li>
  <li> helpful - helpfulness rating of the review, e.g. 2/3 </li>
  <li> reviewText - text of the review </li>
  <li> overall - rating of the product </li>
  <li> summary - summary of the review </li>
  <li> unixReviewTime - time of the review (unix time) </li>
  <li> reviewTime - time of the review (raw) </li>
</ul>
<p>
As part of the data pre-processing and preparing the training data for classifiers we would be first splitting the reviews based on the polarity to positive and negative classes. Also we will use the NLTK in python for the purpose of lemmitizer and removal of stop words to clean the data.
</p>
<h2> Methodology  </h2>
<p>
We will be applying the following approaches to perform sentimental analysis on the Amazon baby products review dataset. We will compare the approaches individually and analyze their performance metrics using parameters such as accuracy, precision, recall and F1-
score. 
<ul>
  <li> K-Nearest Neighbour </li>
<li> Support Vector Machine </li>
<li> LSTM with Word2Vec </li>
<li> LSTM with Glove Model </li>
<li> Multionomial Naive Bayes Classifier </li>
<li> Logistic Regression </li>
<li> Adaboosting </li>
</ul> 
Took the help of NLP tool kit and scikit-learn library in the anaconda distribution of
python and used Google Colab's GPU for reducing the computation time.
 </p>
<h2> Results </h2>
