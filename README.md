# Movie Recommendation Engine

This repository contains the code for building movie recommendation engine.


## Details about Dataset

All the information related to dataset is described in this section.

### Dataset 

* We have used MovieLens dataset in order to build movie recommendation engine. 
* You need to download dataset from [this link](https://drive.google.com/drive/folders/1JnQXDCsGAb75I4PRRMDHUO0WxmXT-usv?usp=sharing)
* Put dataset inside input_data folder. 


### Types of dataset

1. **The full dataset:** This dataset consists of 26,000,000 ratings and 750,000 tag applications applied to 45,000 movies by 270,000 users. Includes tag genome data with 12 million relevance scores across 1,100 tags.
2. **The small dataset:** This dataset comprises of 100,000 ratings and 1,300 tag applications applied to 9,000 movies by 700 users.
3. We will build a simple Recommendation for movies using **The full dataset**.


### Data description
* It contains 100004 ratings and 1296 tag applications across 9125 movies. These data were created by 671 users between January 09, 1995 and October 16, 2016. This dataset was generated on October 17, 2016.

* Users were selected at random for inclusion. All selected users had rated at least 20 movies. No demographic information is included. Each user is represented by an id, and no other information is provided.

* The data are contained in the following files.

credits.csv
keywords.csv
links.csv
links_small.csv
movies_metadata.csv
ratings.csv
ratings_small.csv

<<<<<<< HEAD
## Install dependencies


#### Linux OS (Ubuntu 16.04 LTS / Ubuntu 17.10)


##### Commands for installing pip package manager for ⁠ python3 ⁠

Step 1: $ sudo apt-get -y install python3-pip
Step 2: $ sudo pip3 install --upgrade pip
Step 3: $ pip3 --version

##### Commands for installing all dependencies are given below. 

```
nltk:             $ sudo pip install nltk
numpy:            $ sudo pip install numpy
scipy:            $ sudo pip install scipy
scikit-learn:     $ sudo pip install -U scikit-learn
scikit-surprise:  $ sudo pip install scikit-surprise
Pandas:           $ sudo pip install pandas
matplotlib: 
                  $ sudo apt-get install libfreetype6-dev libpng-dev
                  $ sudo pip install matplotlib 
seaborn:          $ sudo pip install seaborn
jupyter notebook: $ sudo apt-get -y install ipython ipython-notebook
                  $ sudo -H pip install jupyter
jupyter lab       $ sudo pip install jupyterlab
textblob          $ sudo pip install textblob
```    
=======
 
More details about the contents and use of all these files is given in README.txt

### Download dataset 
In-case, there is need to download dataset then use either of the given links.
* If you wnat to download MovieLens dataset hosted on Kaggle then use [this link](https://www.kaggle.com/rounakbanik/the-movies-dataset/data)
* If you want to download MovieLens dataset from its official website then use [this link](https://grouplens.org/datasets/movielens/latest/)


### List of other dataset

* MovieLens - Movie Recommendation Data Sets [link](https://grouplens.org/datasets/movielens/)
* Netflix Prize Dataset [link](http://academictorrents.com/details/9b13183dc4d60676b773c9e2cd6de5e5542cee9a)
* Yahoo! - Movie, Music, and Images Ratings Data Sets [link](https://webscope.sandbox.yahoo.com/catalog.php?datatype=r)
* Cornell University - Movie-review data for use in sentiment-analysis experiments [link](http://www.cs.cornell.edu/people/pabo/movie-review-data/)
* MovieTweetings - [link](https://github.com/sidooms/MovieTweetings)


## Dependencies

* Python >=3.5
* pandas
* numpy
* scipy
* scikit-learn
* scikit-surprise
* lightfm
* matplotlib
* seaborn
* jupyter notebook
* jupyter lab
* textblob


##### Commands for installing all dependencies are given below. 

```
nltk:             $ sudo pip install nltk
numpy:            $ sudo pip install numpy
scipy:            $ sudo pip install scipy
scikit-learn:     $ sudo pip install -U scikit-learn
scikit-surprise:  $ sudo pip install scikit-surprise
Pandas:           $ sudo pip install pandas
matplotlib: 
                  $ sudo apt-get install libfreetype6-dev libpng-dev
                  $ sudo pip install matplotlib 
seaborn:          $ sudo pip install seaborn
jupyter notebook: $ sudo apt-get -y install ipython ipython-notebook
                  $ sudo -H pip install jupyter
jupyter lab       $ sudo pip install jupyterlab
textblob          $ sudo pip install textblob
```    
##### Commands for installing pip package manager for ⁠ python2 ⁠
Step 1: $ sudo apt-get -y install python-pip
Step 2: $ sudo pip2 install --upgrade pip 
               OR 
        $ sudo pip install --upgrade pip

Step 3: $ pip2 --version
              OR
        $ pip --version
