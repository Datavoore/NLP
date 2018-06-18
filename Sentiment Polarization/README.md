# Sentiment Polarization

This project was made to allow the classification of sentences into either positive or negative.

## Getting Started

This notebook contains different functions to simplify some NLP tasks like the cleaning of the data and the vectorization of the data thanks to a Word2Vec model.

The classification is made thanks to a Neural Network built with Keras.

To use the code provided here, you'll need some datasets with positive or negative labelled sentences.

### Prerequisites

To run this code, you'll need the following python librairies :

* Numpy
* Gensim
* Nltk
* Sklearn
* Keras

### Datasets

For this work, I used different datasets gathered online. You can find them here :
* [Sentiment Labelled Sentences Data Set](https://archive.ics.uci.edu/ml/datasets/Sentiment+Labelled+Sentences)
* [Movie review Data Set](http://www.cs.cornell.edu/people/pabo/movie-review-data/)
* [Books and Movies review](https://www.kaggle.com/c/si650winter11/data)

I also used the already trained Word2Vec model over GoogleNews. The binaries to use in the code are available here : [GoogleNews Word2Vec model](https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit)

## Authors

* **Robin Niel** - *Initial work* - [Datavoore](https://github.com/Datavoore)

See also the list of [contributors](https://github.com/Datavoore/NLP/tree/master/Sentiment%20Polarization/contributors) who participated in this project.

## Acknowledgments

* The architecture of the Neural Network was inspired by the following article : [A_Deep_Architecture_for_Sentiment_Analysis_of_News_Articles](https://www.researchgate.net/profile/Khuong_Vo2/publication/318167269_A_Deep_Architecture_for_Sentiment_Analysis_of_News_Articles/links/5a2ea961aca2725814f69b87/A-Deep-Architecture-for-Sentiment-Analysis-of-News-Articles.pdf)


