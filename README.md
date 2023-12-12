# Machine_learning_Recommedation

# Overview
As the people easily get information through media these days, book sales rate was getting decreased so we planned to make book recommendation system using three different method that can help improve book sales.

1. Collaborative filtering(user-item)
2. Content based filtering
3. Apriori algorithm
4. KNN algorithm

Used Book-Crossing dataset from kaggle.

link: https://www.kaggle.com/datasets/ruchi798/bookcrossing-dataset

# Contributor
구건호  김관일  김세중  안지오

# Architecture
<h3>1. Collaborative filtering</h3>

![image](https://github.com/sejung-kim/Machine_learning_Recommedation/assets/82256962/c2c05183-70fe-4801-ae5a-bd73929c8f30)

2. Content based filtering
![image](https://github.com/sejung-kim/Machine_learning_Recommedation/assets/82256962/d5111d06-b628-4f2a-8812-18cf15ffbc78)
3. Apriori
![image](https://github.com/sejung-kim/Machine_learning_Recommedation/assets/82256962/47e7f280-58d7-4894-b7ec-95b5b565dd2e)
4. KNN
![image](https://github.com/sejung-kim/Machine_learning_Recommedation/assets/82256962/e104719c-97f8-4101-8a44-ffad2e6bda3b)
![image](https://github.com/sejung-kim/Machine_learning_Recommedation/assets/82256962/f770a521-4078-455d-8ce0-92726f2c84d5)

# Analysis
![image](https://github.com/sejung-kim/Machine_learning_Recommedation/assets/82256962/e55969dc-93ed-4a9e-ac5d-e795623ed881)
Content-based and collaborative are configured to recommend books based on Book-Title
Compare : They show the results of recommend books with similar title; But They not same recommend list

Analysis
- Collaborative filtering is recommended by obtaining similarity between users rating and item
- Content based filtering is recommended by calculating vector spaces model between words in the book title.



We chose “Harry Potter and the Sorcerer's Stone (Harry Potter (Paperback))" input book. The ideal result for our team was to recommend another Harry Potter series. Four genres of collaborative filtering and content-based filtering recommend the Harry Potter series, but the other one had an unexpected book. Also, the recommendations didn't match completely. We thought that content-based filtering could show similarity and different results between user-items because it calculates the similarity by calculating the word vector of the book title.
![image](https://github.com/sejung-kim/Machine_learning_Recommedation/assets/82256962/87aae010-0a11-4ec9-8558-53346fa75ccd)
In fact, when we searched for "Harry Potter and the Sorcerer's Stone (Harry Potter (Paperback))" on Amazon, we saw that they were recommending books similar to our recommendation system. This may be because Amazon also has a recommendation algorithm based on content-based filtering and collaborative filtering.
If we analyze our system with just one test result, we can think that the content-based method performed the best. However, if you think about it more, books recommended in other ways may be attractive to users. So our team decided that evaluating the recommendation system is really difficult and that there is no absolutely optimal recommendation system.

