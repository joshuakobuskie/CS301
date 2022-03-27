# CS301 Course Project
## Project Proposal - Joshua Kobuskie, Samantha Bellofatto, Sarthak Mital
&nbsp;&nbsp;&nbsp;&nbsp;The problem our group will be investigating is the “H&M Personalized Fashion Recommendations” project. Through this project, we will investigate personalizing product recommendations using artificial intelligence and machine learning based on customer and product metadata. This is a very interesting challenge because of its real world applications. H&M, along with many other online retailers, is always looking to increase sales and improve their customer experience. By exploring this project, we will be able to gain a deeper understanding of machine learning and also apply it to a meaningful purpose that could be utilized in future career opportunities. To provide context and background into the field of machine learning and product recommendations, we will be examining ["THE USE OF MACHINE LEARNING ALGORITHMS IN RECOMMENDER SYSTEMS: A SYSTEMATIC REVIEW"](https://www.ijrar.org/papers/IJRAR19K2241.pdf).<br>
&nbsp;&nbsp;&nbsp;&nbsp;To train our machine learner(s), we will be utilizing the data provided by H&M including images of each product, metadata for each product and customer, and training data consisting of the purchases each customer made on each date. As per the project description, we can choose to “investigate a categorical data type algorithm, or dive into NLP and image processing deep learning.” At this time, we plan to implement a multi-label classification learner focused on categorical data. We will analyze the transactions dataset and customer metadata to predict the probability of a customer buying a specific product. If the probability of purchasing is higher than a threshold, we will predict that the product will be bought by that customer. There are many multi-label classification algorithms that can be used as a reference point for our model. We plan to utilize the standard conventions for an imbalanced classification model and will adapt it to fit our data. We will then optimize the thresholds for determining if a product is predicted to be purchased by a customer.<br>
&nbsp;&nbsp;&nbsp;&nbsp;Our model will attempt to predict the article_ids each customer will purchase during the 7-day period immediately after the training data period. Thus, to evaluate our results, we will compare the predicted article_ids to the actual article_ids purchased. Qualitatively, we expect to create tables linking customer_ids to predicted article_ids. The probability of any given article_id being purchased could be represented as a bar graph displaying the probability of a specific customer buying any of the specific articles in the next seven days. Quantitatively, we can measure our performance by using typical methods implemented by multi-label classification problems including log loss functions and Brier scores. We can also calculate the Mean Average Precision of the model since that is the value that the Kaggle competition uses to evaluate the submissions.<br>
