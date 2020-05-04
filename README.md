# Automatic-Sarcasm-Detection
Sarcasm Detection in twitter dataset(Ghosh) and reddit comments dataset(Khodak)
The project aims at sarcasm classification on the twitter data and the reddit comments data. 

There have been two datasets used in the project  1) Twitter dataset(Ghosh)  2) Reddit comments dataset (Khodak)

**Folders**
1) Twitter_dataset_Ghosh
	i) Codes - Contains 3 notbook .ipynb files
	ii)Resources - Contains all the raw and the preprocessed data and the outputs at intermediate states 
2) Reddit_dataset_Khodak
	i) Codes - Contains 3 notbook .ipynb files
	ii)Resources - Contains all the raw and the preprocessed data and the outputs at intermediate states 
	
**Dependencies to run the project**
1) Sentistrength tool
2) nltk 
3) Keras
4) Tensorflow
5) numpy
6) scipy
7) gensim
8) sklearn
9) seaborn
10) matplotlib
11) pandas
12) pickle

**Flow for the Ghosh dataset**

1) The raw data has been preprocessed using the twitter_preprocessing file. In the intermediate step the sentistrength tool has to be used for the 
   training and testing data to get the polarites.
2) The embedding_features.ipynb is used to get all the embedding features from the dataset. This step would take a considerate amount of time.
3) The twitter_dataset.ipynb file has all the models used in the project for Ghosh dataset. 

**Flow for the Khodak dataset**

1) The raw data has been preprocessed using the reddit_preprocessing file.
2) The sentiment.ipynb file is used to generate a sentiment model which is used as a pre trained model in the latter phase of project.
3) The reddit_dataset.ipynb file has all the models used for classification in Khodak dataset.

	
