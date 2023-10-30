###HonoursProject
##This is an implemenation of IsiZulu Genre Classification model
In this project we have used FastText and Word2Vec word embeddings

In order to run the software you need the isiZulu dataset,
Download the dataset from the SaDiLAR website.
Here's the link to the dataset,
https://repo.sadilar.org/handle/20.500.12185/430 , but I have attached the folder together with the sofware.

The pre-trained fastText word vectors for isiZulu are from this link https://fasttext.cc/docs/en/pretrained-vectors.html, but I have attached the folder together with the sofware.

We have also implemented our own word embeddings :
Word2vec vectors for isiZulu language
Here's the link to the folder with the embedding models.
https://stuukznac-my.sharepoint.com/personal/dlaminis4_ukzn_ac_za/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fdlaminis4%5Fukzn%5Fac%5Fza%2FDocuments%2FPUBLIC%20FOLDERS%2FisiZulu%20Embedding%20Models&ct=1698674316754&or=OWA%2DNT&cid=8efb418d%2Da07e%2Da3d6%2Daca3%2D65b831b01019&ga=1 , but I have attached the folder together with the sofware.

The setup for the FastText word Vectors

Data pre-processing.

Install FastText
pip install Fasttext

import all necessary libraries
Numpy,
Pandas,
Matplot, for visualization of dataset
TensorFlow
Sklearn import the classifiers
Nltk

Load using KeyedVectors.load_format method from gensim word vectors

Text cleaning
download the english nltk stopwords from nltk
import nltk

Split the data to train and test data with a test size of 0.2
Using train_test_split

Download nltk from punkt from nltk

Convert text data into vector representation using fasttext pre-trained model

Classify the model using Random Forest, KNN, SVC,Logistic Regression

And then you fine-tune your classifiers.
Lastly we evaluate results using presicion, recall, confusion matrix, classification report and we conclude based on the accuracy of the classfier

##For Word2Vec pre-trained model

The process is still the same the only differences is that in the word2Vec model you load the pre-trained model using  Word2Vec method from gensim.models



######################################################################################
## TO BE NOTED
Necessary changes are the directory of the dataset, pre-trained models,
NECESSARY CHANGES ARE THE DIRECTORY OF THE DATASET, PRE-TRAINED MODELS

