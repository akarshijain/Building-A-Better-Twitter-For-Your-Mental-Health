# Building A Better Twitter For Your Mental Health

Social media has become an integral part of our day-to-day life. People use it not only to share their personal life’s updates but also to promote and run businesses. The growing use of social media provides a fertile ground for hackers to commit cybercrime. Most cybercrimes today are undertaken through fake social media profiles thereby leading to threat and loss of individual's personal information. Many studies have shown that acts of cybercrime affect an individual's mental health in an adverse manner. Researches have developed various machine learning algorithms to detect fake accounts efficiently. This project applies three machine learning algorithms namely, K-Means Clustering, Naive Bayes and Decision Tree on MIB Twitter Dataset. A comprehensive comparison among these algorithms is shown on the basis of Recall, Precision, Accuracy and F-measure. The final results show that Decision Tree gave better results with an accuracy of 98.75%.


## Methodology

Link to dataset: [MIB Twitter Dataset](http://mib.projects.iit.cnr.it/dataset.html)

1. Data is collected from MIB Twitter Dataset.
2. Cleaning the data to remove unwanted data, missing values, duplicate values, data type conversion, etc. 
3. Visualising the data.
4. Splitting the data into training and testing set.
5. Training the model and fitting the training set.
6. Evaluating the model on the basis of Recall, Precision, Accuracy and F-measure.

## Dataset Features

| Parameters | in Twitter terms |
|--|--|
| status_count | number of tweets |
|followers_count|followers|
| friends_count | following |
|favourite_count|no. of likes|
|listed_count |no. of list |


## Results

#### K-means Clustering
| Metrics | Value |
|--|--|
| Recall | 35.67688855646971 % |
| Precision | 44.746716697936215 % |
| Accuracy | 48.5805535841022 % |
| F-measure | 39.70037453183521 % |

#### Naive Bayes
| Metrics | Value |
|--|--|
| Recall | 98.56630824372759 % |
| Precision | 80.64516129032258 % |
| Accuracy | 87.58865248226951 % |
| F-measure | 88.70967741935483 % |

#### Decision Tree
| Metrics | Value |
|--|--|
| Recall | 97.25490196078431 % |
| Precision | 100.0 % |
| Accuracy | 98.75886524822694 % |
| F-measure | 98.60834990059641 % |

We observe that Decision Tree gave better results than K-means Clustering and Naive Bayes algorithm.