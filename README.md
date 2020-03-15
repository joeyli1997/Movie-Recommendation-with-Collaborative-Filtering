# Movie Recommendation with Collaborative Filtering


### Introduction
Collaborative filtering algorithms are being used all around us, as these recommendation systems are personalizing the way we enjoy movies, television, music, and more. Movie recommendation systems such as the one used by Netflix are leveraging our rating patterns and those of other users to predict what we might like to watch next. The goal of this model is to use collaborative filtering to predict how individuals may rate movies they have not seen or have not rated.

### Data Description
The data for this analysis was obtained by Professor Ashwin Aravindakshan, who sent out a survey to 98 MSBA and MBA students. The survey contained 50 movie titles, and students were asked to rate on a scale of 1-5 as many of the 50 movies listed as they had watched. Ratings of an additional 40 individuals were also obtained to increase potential prediction accuracy.

### Model Development
Collaborative filtering models are a common and simple approach to building recommendation systems. Collaborative filtering models can be approached in two ways: memory-based and model-based . The approach used to develop our model is memory-based. Memory-based approaches use either user-user or item-item filtering to predict user movie ratings. User-user filtering focuses on a specific user, finds other users that gave similar ratings on watched movies, and recommends items that those similar users liked. On the contrary, item- item filtering will take an item -- which is a movie in our context -- find users who like that movie, and find other movies that the users liked; item-item filtering takes movies as input and outputs other movies as recommendations.

![pic1](/figure1.png)

### Conclusion
These predictions based on the recommendation algorithm provide value to firms because the personalization the algorithm creates can lead to higher customer satisfaction. The collaborative filtering models that we applied to the recommendation system can give us accurate predictions on users’ rating if provided with enough information. However, a drawback of the model is its lack of interpretation power. In other words, it cannot inform us the variables that have impact on the ratings and quantify their impact. Therefore, it is not able to go beyond prediction. In order to equip our model with interpretation power, we can integrate the result of collaborative filtering with regression and classification methods. Knowing the contributor variable to the high ratings, business strategies can be deployed to increase users’ satisfaction on the overall content provided by the media platform. The predictions will become more precise with more data, yet the accuracy is still contingent on the accuracy of the initial model created, making the investment in the initial model build all the more important. Without recommendation systems, firms cannot easily personalize customers’ experiences, and customer retention would be much more difficult.
 

### Citations
Grover, Prince. “Various Implementations of Collaborative Filtering.” Medium, Towards Data Science, 18 Dec. 2018, towardsdatascience.com/various-implementations-of- collaborative-filtering-100385c6dfe0.
Rocca, Baptiste. “Introduction to Recommender Systems.” Medium, Towards Data Science, 12 June 2019, towardsdatascience.com/introduction-to-recommender-systems-6c66cf15ada.
Topor, James. “User-Based and Item-Based Collaborative Filtering.” RPubs, 11 June 2017, rpubs.com/jt_rpubs/285729.




