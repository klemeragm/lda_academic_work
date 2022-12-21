# lda_academic_work
This is my repository of my final work and some files about the them of the same. 
This project is about processing modeling using LDA in order to group story fragments using pre-processing techniques and storage modeling

# Pre-requisites
Its necessary have to install the python 3x or higher and have the libraries installed below (in some cases anaconda requires installation with conda install name-library)


# Install unicodedata
The library will helps in Cleaning to remove all ASCII and the majority ponctuations 

pip install unicodedata or conda install unicodedata 

# Install NLTK 
NLTK(Natural Language Toolkit)

<href="https://www.nltk.org/book/">Natural Language Processing with Python</a> provides a practical introduction to programming for language processing.
To Lemmatize and Stemer the sentences and cut the language stems 

pip install nltk 

# Installing required packages

After NLTK has been downloaded, install required packages

import nltk
from nltk.stem import WordNetLemmatizer
nltk.download('popular', quiet=True) # for downloading popular packages
nltk.download('punkt') 
nltk.download('wordnet') 

# Install the world cloud package to mapping and use the EDA Techniques to view the words
pip install WordCloud or conda install WorldCloud

# Install pyLDAvis
The Library can help evaluate the model in the clusters. In this project we can use inline the aplication to validate the entraces of the model. 

pip install pyLDAvis or conda install pyLDAVis 








