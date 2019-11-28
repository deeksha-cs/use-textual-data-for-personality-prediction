# use-textual-data-for-personality-prediction
# Abstract
Personality is an important parameter as it differentiates various individuals from one another. Personality prediction is 
an evergreen area of research. Predicting personality with the help of data through social media is a promising approach as this method does not require any questionnaires to be filled by users thus reducing time and increasing credibility. 
Thus having knowledge of personality is an interesting domain for researchers to work on. Predicting personality has many applications in real world. Use of social media is increasing day by day. Huge amount of textual data as well as images continue to explode to the web daily. Current work focuses on Linear Discriminate Analysis, Multinomial Naive Bayes and AdaBoost over Twitter standard dataset.
Keywords—Machine Learning, Big Five test, Social Media, Statistical analysis.  
 
 
 #Introduction 

Personality is a key aspect of human life. More specifically personality is a branch of psychological study. Personality is constituted 
of elements like person’s thoughts, feelings, behavior which continuously keeps on changing over time. Prediction of personality is an area of study where person gets categorized in a class according to his/her personality. There are number of psychological tests that yield different type of personality classes. Popular tests include Big Five test [1, 2, and 3] which yield personality classification in five categories as openness to experience, conscientiousness, extraversion, agreeableness and neuroticism. DISC is another test of psychology that classifies personality in categories as Dominance, Influence, Steadiness and Compliance [4]. MBTI psychological test has 16 categories of personality [5, 6]. All these traditional methods of personality prediction use questionnaire for personality prediction. Filling a lengthy questionnaire is time consuming and tedious job. 
Advanced machine learning algorithm - AdaBoost has been used in [8] for prediction. Boosting algorithms are used to gain highest accuracy and high performance. Hence we have employed AdaBoost with other algorithms like LDA and Multinomial Naïve Bayes to analyze accuracies of algorithms

Social media is a promising approach for this task. It is easier to gather a dataset from social media like Twitter or Facebook and use it for prediction. Hence in this work we have used real-time Twitter dataset for predicting personality. Twitter provides API like Twitter streaming API [7] which is useful for building dataset.


# Future scope
 It is clear from literature overview that there has been extensive work happened in the domain of personality prediction still there are multiple areas 
 needed to be focused. Personality is a broad domain and it comes under psychological studies.In this work we have focused mainly on Big
 seven model of personality prediction which contributes to five categories of personality .There is a scope of research in combining multiple tests of personality to find most accurate class labels. Also more focus can be thrown on real-time data which can have significance with real world. Combining Machine Learning algorithms can be useful in improving accuracy. Lastly, there is a scope to work in multimodal approach of prediction in which different biomedical signals can be considered.    

# Conclusion

Psychology is a broad domain of study and personality prediction is its integral part. Social media is a most promising platform to determine 
personality of a person. In the world full of competition, everyone is not able to present his/her views to the world. Hence social media like Twitter, Facebook or Instagram etc. proves most promising solution in this scenario. People express their opinion completely on such platforms without thinking whether they are right or wrong.
Hence personality prediction helps in such scenarios where it is easy to compute sentiment of a tweet or post posted by user by applying algorithms.
As discussed in our work we have applied Multinomial Naïve Bayes, AdaBoost and LDA to compare which algorithm has higher relevance. Thus, according to our results it is found that Multinomial Naïve Bayes has highest accuracy of 73.43, precision of 0.7, and recall of 0.71 and F1-score of 0.72. Future scope aims in improving accuracy of algorithm.
