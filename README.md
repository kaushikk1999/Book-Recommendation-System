# Book-Recommendation-System
This is a book recommendation system that uses a user-based collaborative filtering method to recommend books to users. The system takes as input a user's past ratings of books, and then uses this information to recommend other books that the user is likely to enjoy.  The system is implemented in Python using the Surprise library. 
Book Recommendation System
This is a book recommendation system that uses a user-based collaborative filtering method to recommend books to users. The system takes as input a user's past ratings of books, and then uses this information to recommend other books that the user is likely to enjoy.

Installation
To install the system, you will need to have Python 3 and the Surprise library installed. You can install the Surprise library by running the following command:

pip install surprise

Usage
To use the system, you will need to provide a file containing the user ratings of books. The file should be in the following format:

user_id,book_id,rating
1,123456,5
2,123456,3
3,123456,4

Once you have provided the file of user ratings, you can then run the system by executing the following command:

python book_recommender.py <path to ratings file>


The system will then output a list of recommended books for each user.

## Features

The system has the following features:

* User-based collaborative filtering
* Implementation in Python using the Surprise library
* Ability to recommend books to users based on their past ratings
* Ability to recommend books to users even if they have not rated many books
