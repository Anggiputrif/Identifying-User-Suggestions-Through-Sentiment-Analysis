# Identifying-User-Suggestions-Through-Sentiment-Analysis
Research Background :
Bijak Memilih Platform is an application developed by an independent organization to provide information for the public related to the implementation of political activities. However, this platform is still a relatively new platform so it still needs a lot of input for its development. This is in accordance with their future target, which is to develop the platform based on feedback from social media. 

Methods :
This research uses 3000 data sourced from comments on Bijak Memilih’s social media posts that contain platform explanations. The sentiment classification process resulted in 1116 data point with negative sentiments that were tagged using POS Tagging.
This project goes through several stages, including: 
•	Sentiment analysis process using Naive Bayes Classifier algorithm to identify sentiments from opinions
•	POS Tagging process using HMM-Viterbi to identify the object of discussion through filtering the class labels of nouns, verbs, and adverbs. 
•	The process of identifying word combinations that often appear together using the a priori algorithm so as to obtain meaningful information from the relationship between words.

Result :
The final results identified ten discussion objects along with related words, which were concluded as user suggestions. The discussion objects describe specific issues and features that are proposed for addition or improvement on the Bijak Memilih platform, including :
1)	additional features for ranking parties involved in corruption
2)	additional features for profiles of candidates who have been corruptors
3)	additional features for summary of corruption from all parties in visual form
4)	creation of a mobile application to facilitate access
5)	reconsider the presentation of the opposing ideologies of Pancasila and Islam
6)	mentioning the names of party cadres involved in corruption cases, but not limited
7)	additional features for the completion and success of ministry programs
8)	additional discussion of party views on asset forfeiture
9)	additional discussion of election-winning party policies
10)	additional darkmode settings on the screen display.
The classification test results shows the highest accuracy of 94% and POS Tagging shows an accuracy of 93%.

