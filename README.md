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

## Install dependencies


#### Linux OS (Ubuntu 16.04 LTS / Ubuntu 17.10)


##### Commands for installing pip package manager for ⁠ python3 ⁠

Step 1: $ sudo apt-get -y install python3-pip
Step 2: $ sudo pip3 install --upgrade pip
Step 3: $ pip3 --version


##### Commands for installing pip package manager for ⁠ python2 ⁠
Step 1: $ sudo apt-get -y install python-pip
Step 2: $ sudo pip2 install --upgrade pip 
               OR 
        $ sudo pip install --upgrade pip

Step 3: $ pip2 --version
              OR
        $ pip --version
