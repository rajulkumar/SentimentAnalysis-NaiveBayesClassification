Sentimental Analysis using Naive Bayes Classificaiton
-----------------------------------------------------
This is an implementation of binary classification of the text using textual figures like unigrams, bi-grams and binary relevance of the words in a document. It is used to anayse the sentiments of the users based on the reviews they write for a movie as good or bad. First the system is trained using pre-classified data for the good and bad reviews by the users. Based on this, a model file is generated that is used in classifying the reviews based on sentiments of the users.

The source code is present in SentAnalysis_unigram directory whereas modified version of the same program is present in "Modified Version" directory

 How  to run: 
-------------------------------------------------------------
 If running on console:

 1.Save NBTrain.java and NBTest.java on disk .
 2.Compile the java file by giving below command: 

 javac NBTrain.java 
 javac NBTest.java
 
 3. Run by giving the command 
 java NBtrain <location of the train data> <File Path of model file>
 java NBTest <File Path of model file>

Assumption:
Train data should have two folders as "pos" and "neg" at train data location.

-----------------------------------------------------------------

 If running on eclipse:
 
1. Import the package
2. Give the command line argument through Run->Configuration->Command Line Argument as 
   <location of the train data> <File Path of model file>
3. Run


Test Results:
-----------------------------------------------------------

The classification result is present in ./results/test location.
Along with positive to negative and neagative to positive term counts and top 20 ratios as well.
