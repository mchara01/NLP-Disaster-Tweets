## NLP with Disaster Tweets

### Description:
Twitter has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency 
they are observing in real-time. Because of this, more agencies are interested
in programmatically monitoring Twitter (i.e. disaster relief organizations and
news agencies).

But it’s not always clear whether a person’s words are actually talking about
a legitimate disaster. 

In this project, we started by inspecting our dataset to gain any useful information about
what kind of text we are facing by the use of plots during the EDA analysis phase and then 
proceeded to check a plethora of relevant text processing models and subsequently choosing 
the best and ultimately proceed in the best possible prediction.

More specifically, what we achieved is developing a machine learning model and applied Natural
Language Processing techniques that predicts which Tweets are about real disasters(predict 1)
and which ones aren’t(predict 0). For the project's purpose we where given access to a dataset
of 10,000 tweets that were hand classified.

Evaluations are done using F1 between the predicted and expected answers.

Each sample in the train and test set has the following information:

-The id of a tweet

-The text of a tweet

-A keyword from that tweet (may be blank)

-The location the tweet was sent from (may be blank)

train.csv: Dataset used for model building which contains the above columns.

### How to run:
`python disasters.py`<br />
`python parameter_tuning_logistic_regression.py`<br />
`python ngrams_feature_selection.py`<br />
`python submit.py` (If sumbitting to the competition is desired)<br />

Warning: There are many non-default modules installed in this project. Please install anaconda first and then
install any other missing module using pip install <name of module> needed to successfully execute the files
in this project.

Details about our work can be found at the report Report_Team3.pdf and powerpoint EPL448-Team3_Final. Further documentation can be referenced in the appendix(of  the report) and output files.

More info about the competition can be found at the competition's offical page on Kaggle: https://www.kaggle.com/c/nlp-getting-started

### Authors
* Marcos Antonios Charalambous (mchara01@cs.ucy.ac.ucy)
* Sotiris Loizides (sloizi02@cs.ucy.ac.ucy)
		  
**Date:** 26/04/2020
