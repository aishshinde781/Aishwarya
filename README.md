Movie recommender system

table of content

 1.Demo
	
 2.Overview
 
 3.Introduction
	
 4.Technical Aspect
 
 1.Demo
  Link:https://mrs-aishwarya.herokuapp.com/
 
 2.Overview
  This is a simple movie recommendation app which recommends movie according to our interst or our searches.
 
 3.Introduction
  Recommendation systems are computer programs that suggest recommendations to users depending on a variety of criteria.

   These systems estimate the most likely product that consumers will buy and that they will be interested in. Netflix, Amazon, and other companies use recommender  systems to help their users find the right product or movie for them.
	 
 There are 3 types of recommendation systems.

 1. Demographic Filtering : The recommendations are the same for every user. They are generalized, not personalized. These types of systems are behind sections like “Top Trending”.
 2. Content-based Filtering : These suggest recommendations based on the item metadata (movie, product, song, etc). Here, the main idea is if a user likes an item, then the user will also like items similar to it.
3. Collaboration-based Filtering : These systems make recommendations by grouping the users with similar interests. For this system, metadata of the item is not required. 

4.Technical Acpects
This project is divided into two part:

Training a machine learning model using 
Building and hosting a Flask web app on Heroku.
A user can choose image from a device or capture it using a pre-built camera.
Used Amazon S3 Bucket to store the uploaded image and predictions.
Used CSRF Token to protect against CSRF attacks.
Used Sentry to catch the exception on the back-end.
After uploading the image, the predictions are displayed on a Bar Chart.
 

