Coffee House Recommendation Service System using Azure Machine Learning Studio

Project Link : https://gallery.cortanaintelligence.com/Experiment/Coffee-House

Problem Statement: 

Every time people face difficulties in determining the quality of a local business. Local business here refers the coffee house, and it becomes more challenge to choose the coffee house for new users and they may not know the customer services, their beverage quality and the equipment usage and they may not aware of professional staffs who are hired there so we are jumped into a rating system. And how to correctly interpret search requests based on people’s preference is a challenge.

Project Description:

The thesis uses a Azure Machine Learning (ML) by which the ratings from the registered users to generate a machine learning model that helps to satisfy the problem of determining the quality of coffee house by providing the ratings of User ID for the corresponding coffee-house ID. I have implemented this by using Train Matchbox Recommender that reads the datasets and  can learn about a user's preferences through observations made on how they rate items, such as movies, content, or other products.
Moving further into the project we have to upload the necessary data into a .csv file format. 
I have a three csv files namely 

-Coffee-House-Customer-data containing UserID, latitude and longitude Birth year, Personality, Budget, Their proffesion, Drink level.

-Coffee-House-Feature-data containing PlaceID, latitude and longitude, Name, Address, City, State, Country, Price.

-Coffee-House-ratings containing UserID, PlaceId and its Ratings.

Once collected a sufficient ratings from a particular users and can make predictions for the new users by the ratings given by the registered users. This will work based on collaborative filtering with a content based approach.
