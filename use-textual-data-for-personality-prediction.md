
        
# Using Textual data for personality prediction :  A Machine learning approach
 

        
# SYNOPSIS 


Institute of Engineering & Technology 

Team Members

Deeksha Agrawal
171500090

Sonal Agrawal
171500342

Supervised By
Techanical Trainer
Sonia Mam

Department of Computer Engineering & Applications


About the Project: 
   

Personality is an important parameter as it differentiates various individuals from one another. Personality prediction is an evergreen area of research. Predicting personality with the help of data through social media is a promising approach as this method does not require any questionnaires to be filled by users thus reducing time and increasing credibility. 
 Thus having knowledge of personality is an interesting domain for researchers to work on. Predicting personality has many applications in real world. Use of social media is increasing day by day. Huge amount of textual data as well as images continue to explode to the web daily. Current work focuses on Linear Discriminate Analysis, Multinomial Naive Bayes and AdaBoost over Twitter standard dataset.

Keywords—Machine Learning, Big Five test, Social Media, Statistical analysis.  

Social media is a promising approach for this task. It is easier to gather a dataset from social media like Twitter or Facebook and use it for prediction. Hence in this work we have used real-time Twitter dataset for predicting personality. Twitter provides API like Twitter streaming API [7] which is useful for building dataset.


Experimentation and results:

Dataset Creation:

Following are the steps to fetch real-time data from twitter.
 In order to collect tweets from Twitter, one needs to 
have a Twitter account.
 After logging in to your Twitter account go to 
Twitter developer settings and follow the steps 
specified by the developers. 
 After all the processing is completed, you will get 
‘Twitter APIKey’ and ‘APISecret’ key which are 
needed to be used in python program to fetch tweets 
from Twitter.
Python provide library named ‘Tweepy’ which is important for processing. 


Preprocessing:

As discussed in section II, data need to be preprocessed in order to achieve expected accuracy. Data mining provides the feature for data pre-processing which is required for cleaning the data, removing outliers and inconsistencies. For the current work we have used and replaces through preprocessing steps like tokenization, stemming and removing of stop words.
 First text of the dataset ‘likes the sound of thunder’ has been converted to ‘like sound thunder’ ,this indicate stopwords like ‘the’ and ‘of’ are removed in 
stopword removal process.
 ‘is sore and wants the knot of muscles at the base of her neck to stop hurting. On the other hand, YAY I'M IN ILLINOIS! <3’ has been converted to ‘sore want knot muscl base neck stop hurt yay illinois’ ,thus here all the capital letters has been converted to lower case and special symbol ‘<3 ,!’ also have been eliminated.

Result:

1  comparision of accuracy.
2  comparsion of precision.


Motivation:

Psychology is a broad domain of study and personality prediction is its integral part. Social media is a most promising platform to determine personality of a person. In the world full of competition, everyone is not able to present his/her views to the world. Hence social media like Twitter, Facebook or Instagram etc. proves most promising solution in this scenario. People express their opinion completely on such platforms without thinking whether they are right or wrong.


Future Prospects:

Personality is a broad domain and it comes under psychological studies.
In this work we have focused mainly on Big Five model of personality prediction which contributes to five categories of personality .There is a scope of research in combining multiple tests of personality to find most accurate class labels. Also more focus can be thrown on real-time data which can have significance with real world.
Combining Machine learning algorithms can be useful in improving accuracy. 
Lastly, there is a scope to work in multimodal approach of prediction in which different biomedical signals can be considered.


Refrences:

1] Golnoosh Farnadi, Jie Tang, Martine De Cock, Marie-Francine Moens, 
“User Profiling through Deep Multimodal Fusion”, WSDM’18, Marina Del 
Rey, CA, USA, February 5-9, 2018.
[2] https://openpsychometrics.org/tests/IPIP-BFFM/
[3] Tommy Tandera, Hendro, Derwin Suhartono, Rini Wongso, and Yen Lina 
Prasetio , “Personality Prediction System from Facebook Users”,2nd 
International Conference on Computer Science and Computational 
Intelligence , Bali, Indonesia , 13-14 October 2017.
[4] https://www.discprofile.com/what-is-disc/overview




Requirements:
     
Python, MongoDB, PyMongo, Node.js/npm, Selenium

Software:   Spyder

Hardware: Using 4GB RAM
     



















