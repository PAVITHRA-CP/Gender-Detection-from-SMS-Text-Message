# Gender Detection From SMS Text Message Using Machine Learning
Short message service (SMS) has become a very popular medium for communication due to its convenience and low cost. It is easy to provide a false name, age, gender, and location in order to hide ones true identity. So it becomes imperative to design an efficient method for identity tracing in cyberspace forensics. Here manily focussing on Gender Identification.

# Overview
Comparison of two approach for gender identification is performed:     

	[1] Based on n-gram feature                                                                                                       
	[2] Based On Manually extracted 5-set of features                                                                                

Comparison on two classification algorithm:                                                                                               

	[1] Naive Bayes                                                                                                                   
 	[2] Support Vector Machine(SVM)                                                                                                   

Identify which feature is important to predict the gender                                                                                 

Implementation Language : Python                                                                                                           

n-gram Features : Use tf-idf vectorization                                                                                                 

Manually extracted features :  

	Word based
	Character based
	Syntactic based
	Structural based
	Functional based
	
In these approach SVM outperforms the Naive Bayes model. A study on the important features for identifying the gender shows that syntactic
feature is most essential in identifying the gender.
