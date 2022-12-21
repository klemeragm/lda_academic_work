# lda_academic_work
This is my repository of my final work and some files about the them of the same. 


Este projeto é sobre modelagem de tópicos usando o LDA com o intuito de agrupar fragmentos de histórias usando técnicas de pré-processamento e a modelagem de tópicos



Its necessary have to install the python 3x or higher
É necessário ter o Jupyter Notebook ou um editor de python 3x ou superior

Ter as bibliotecas instaladas abaixo (caso o anaconda requisite a instalação)


# Install unicodedata
The library will helps in Cleaning to remove all ASCII and the majority ponctuations 

pip install unicodedata or conda install unicodedata 

# Install NLTK To Lemmatize and Stemer the sentences and cut the language stems 

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
conda install pyLDAVis
import pyLDAvis 









