# Practical-Application-III
Shem Cheng
2022

**Objective:** The main objective is to compare four classifiers: k-nearest neighbors, logistic regression, decision trees, and support vector machines. To this end, a dataset of customers of a telephone campaign is analyzed. Features of the dataset include age, job, marital status, housing loans, etc., and the target feature is whether or not the customer subscribed to the service being advertised.
Once the relevent features are identified, the dataset is cleaned and modified such that the relevent features can be used to create a training set and a testing set. The training set is then used to train the four classifiers while the testing set is used to test the accuracy of each classifier. Every classifier is aiming to beat a baseline score of 0.795.

**Conclusion:** From the dataset, we can conclude that the number of calls, the duraction of calls affect the likelyhood of the customer subscribing to the advertised service. The higher number of calls, the less likely a customer is to subscribe. The longer duration of a call, the more likely a customer is to subscribe. As such, in terms of behaivior, an advertiser should aim to keep customers on the line for as long as possible while avoiding calling customers who have already been called.

In terms of the customer, from the dataset, we can conclude that people with a lower level of education are more likely to subscribe. Likewise, students and retirees are the most likely people to subscribe. From this, advertisers should focus their efforts on attracting retirees and students. They should also target customers with a lower level of education, though given the fact that the overlap between students and people less education would probably be pretty small, this would most likely apply only to the retirees.

Of these four classifiers, the nearest neighbors classifier has a training time of 0.03 seconds and a test score of 0.904. Logistic regression, meanwhile, has a higher test score of 0.908 which is higher than nearest neighbors. However, it also has a training time of 1.17 seconds, about 39 times slower than nearest neighbors.
