# Fuzzy-Based-Recommendation-System

A Recommender System is an application that  is used to provide insightful recommendations to users that align with their interests.
Based on their preferences and viewing history.


![image](https://github.com/user-attachments/assets/905cdccb-ecf6-4b78-8484-40caf7453575)

Recommender systems plays an essential role in our real life they simplify decision-making , they assists users for finding relevant and personalized content in various domains, such as e-commerce ,social networking, job portals, travel and entertainment etc. 
The system will consider various factors such as  past purchases, search history, demographic information, and other factors to the user.

# Problem-Statement 
It has been observed that most of the users do not give any ratings. So, a research problem arises that how to know whether they are satisfied with the product and how much.
By incorporating the fuzzy membership functions for representing user-item interactions, the system can assign degrees of relevance or the preferences.


Fuzzy logic allows for handling uncertainty and imprecision in data, making it a valuable tool for recommendation systems when dealing with uncertain user preferences and item characteristics It also involves the application of fuzzy logic and fuzzy inference techniques to create a personalized recommendation engine.




# Overview Of Various Methods
There are several approaches to building recommendation systems, and they can be categorized into two main types: collaborative filtering, content-based filtering.


# Collaborative Filtering 
This technique relies on user-item interaction data to identify patterns and make recommendations.   
It recommends items based on the behavior and interest of similar users.
For example: In a music recommendation , if you and another user have same interest and share a lot of common favorite songs and artists. If  that user listens to a new album, the system may suggest same  album to you, assuming  that you'll likely enjoy it too.

# Content Based Filtering
This recommends items to users based on the characteristics or features of the items and the user's preferences.
In a movie recommendation system, it might consider features like genre, actors, director, and user's past preferences. This uses Clustering approaches k-means etc.
For example: If a user browses for a product on an online shopping platform, the platform will analyze the item attributes of the users purchase history and based this information, the system will recommend the similar items to the user.

# Appication of Fuzzy Logic
In this project  involves the application of fuzzy logic  and fuzzy Inference techniques to create a personalized recommendation engine. Fuzzy logic allows for handling uncertainty and imprecision in data, making it a valuable tool for recommendation systems.
Fuzzy logic is a process generalizing the standard logic, in standard logic  which all statements have a truth value of 0 or 1.
In fuzzy logic, statements can have a value of partial truth, such as 0.95 or 0.25 .



![image](https://github.com/user-attachments/assets/9fd14465-1991-4280-ab73-2787eb2b1cec)

# Advantages of Fuzzy Systems 
Handling Uncertainty:  Uncertainty refers to a lack of complete information about a data, when there are errors, incomplete information uncertainty occurs.
Fuzzy Systems are well-suited for situations where user preferences or item characteristics are not clear.
Fuzzy systems use membership functions to represent the degree of truth

Sparse Data: When  a large part of the data-set contains missing values or empty values it leads to data sparsity.. 
Fuzzy systems can handle sparse data, it  creates fuzzy user profiles instead of relying  only on crisp ratings.
 Fuzzy profiles represent the degree of preference or membership of a user to various item characteristics or genres.


#Proposed Models
Cosine Similarity : It is a distance metric used to measure the similarity between two vectors that represent user preferences or item characteristics.
It measures the similarity between two items, such as movies, by calculating the cosine of the angle between their feature vectors.

![image](https://github.com/user-attachments/assets/34c231ba-e77e-4ab9-b9a6-829c2c19dabd)

Fuzzy Systems : Fuzzy means unclear ,distinct or precise .Fuzzy logic is a form of multi-value logic.
                         A = (x, μA(x));  x, μA(x)[0, 1])

In fuzzy sets ,each elements is mapped with [0,1] by the membership function.


# Code Implementation
Using the concept of fuzzy membership functions, the project uses two snippets of code. 

The first snippet contains  one is in Python programming language using the packages like scikit-learn, pandas , and  numpy arrays. 

And the second snippet of code is in the HTML, JavaScript programming language which is used to create interactive web pages. 


![image](https://github.com/user-attachments/assets/404964d9-cf55-4f11-9d19-3bb7e93880ef)



The first part of the code is used to load  the data from excel file using pandas libraries  " pd.read_csv " this extracts user details like gender, age ,occupation and movie details like movie id ,title, genre.
The next part of the code creates fuzzy sets that is based on the user’s ratings .

A class is created that measures the users interest on a particular movie based on genre  that returns good ,bad, very bad, average etc values.
Here, feature extraction methods and distance metrics are utilized to generate recommendations. Feature extraction method is used for calculating similarity between each item available.. 



# Results 


![image](https://github.com/user-attachments/assets/905cdccb-ecf6-4b78-8484-40caf7453575)



![image](https://github.com/user-attachments/assets/e45ac256-7e34-4277-906f-277f8dfd1312)



![image](https://github.com/user-attachments/assets/b7956436-2025-4944-900c-d0dad88e53b5)



![image](https://github.com/user-attachments/assets/1747d4bf-62cc-48d4-8c17-647f3b9c8916)

