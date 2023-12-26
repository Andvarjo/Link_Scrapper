# Link Scrapper 🤖
link Scrapper is a demo solution which uses NLP, Web Scrapping, Translator solutions 
to be able to capture relevant information about a web page and summarize all the content.
It also uses Machine learning Algortihms like SVC, Naive bayes for web classification
using "Website Classification" dataset from Kagle.

# Using the project 🦾

This project is intended to be exposed by a cloud service of your prefrence.
here you can find backend and frontend folders which contains all the necesary files
to run by independent Docker containers(Include Docker files).
Also you cand find and IPYNB notebook for experimenting purposes where you can
run models using deep learning or machine learning and save them to be used as
classification engine.

# Data Path 👀

First scenario: you have a web page link and you want to save info about it on your database.
our firts goal consists in web scrapping, using beautigul soup you capture all the titles, images and text
from the link you provide.
then using Hugging Face transformer tools, al the text data is summarized in order to keep all the relevant information
our title data is stored and processed by our Machine leraning model to be classified.
using Translator tools we can manage all kind of information, our goal is to traduce any kind of
web page to english text.

in the front end you cand save your link, summarize, translate and classify it to be stored on a firebase database


