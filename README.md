# BUILD-A-RECOMMENDATION-SYSTEM-USING-COLLABORATIVE-FILTERING-OR-MATRIX-FACTORIZATION-TECHNIQUES
COMPANY: CODTECH IT SOLUTIONS
NAME: ABHIJEET KUMAR
INTERN ID: CTO4DG2125
DOMAIN: MACHINE LEARNING
DURATION: 4 WEEKS
MENTOR: NEELA SANTOSH
DESCRIPTIONS :
In this project, My aim to build a recommendation system that suggests books to users based on what similar users have liked. I use a method called collaborative filtering, and specifically, a matrix factorization algorithm called SVD (Singular Value Decomposition), provided by the Surprise library in Python.
I work with a Book Recommendation Dataset, which contains user ratings for various books. 
The key idea behind collaborative filtering is that people with similar tastes will rate similar books similarly. 
So, if User A likes the same books as User B, I can suggest books rated highly by B to A.

Step 1: Import Required Libraries
I used Pandas,Numpy,andMatplotlib and scikit-surprise.

Step 2:Load and Prepare the Data
Then, I use a Book Ratings dataset which includes user_id, book_id, and rating.

Step 3: Train And Test Split
Split the data into training and testing sets.

Step 4: Build the SVD Model
I use SVD, a matrix factorization method, to train our model.

Step 5:Test the Model
Then, I Evaluate the model using the test set.

Step 6: Recommend Top-5 Books to a User
After that I recommend some books to a user.

Step 7: Plot Histogram to See How Ratings are Distributed
After building the recommendation model, I want to explore the data a bit more to see how ratings are distributed.
X-axis (Rating): These are the different rating values given by users (e.g., 1, 2, 3, 4, 5).
Y-axis (Frequency): This tells how many times each rating was given.
Tall bars: A tall bar at rating 5 means many users gave 5-star ratings.


#OUTPUT:-
<img width="1666" height="802" alt="Image" src="https://github.com/user-attachments/assets/5c37d8ab-62fd-4713-ade4-7ffdb2d20805" />
