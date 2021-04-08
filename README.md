# nlp_flipkart
ML model made to predict the product class based on it's text description.  
This repository contains a ML Model that is used to classify products under a primary category using it's description.
The dataset used here is from the ecommerce giant Flipkart, the link to which is: https://docs.google.com/spreadsheets/d/1pLv0fNE4WHokpJHUIs-FTVnmI9STgog05e658qEON0I/edit?usp=sharing

## Getting started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
[![Generic badge](https://img.shields.io/badge/pandas-python-red.svg)](https://shields.io/) [![Generic badge](https://img.shields.io/badge/csv-fasttext-<>.svg)](https://shields.io/) [![Generic badge](https://img.shields.io/badge/gensim-blue.svg)](https://shields.io/)
### Installing
Install python from this link according to your system: 
https://www.python.org/downloads/  
Install the above mentioned libraries using pip
```
pip install pandas
```
```
pip install python-csv
```
```
pip install fasttext
```
```
pip install gensim
```
## The model
### Building
To build the model, open the "MIDAS'21_local.ipynb" notebook and run all the cells. Each fragment of the code has an explanation along with it.
### Results
The model yields an accuracy of 78 percent in 70 epochs given the size of the dataset.
### What other approach I could have used?
Another approach could have been the use of SVM's or Naive bias to classify the model. One approach that I think would work better if we are not bound to use the description as the main feature would be the use of the product image. Using ImageGenerator, we could train our network to classify product based on the images.

## Bibliography
https://fasttext.cc/docs/en/supervised-tutorial.html  
www.stackoverflow.com
