## 	Music Recommendation System

### Objective
* Recommend new musical artists to user based on their listening history. 
* Used Altering Least Square Algorithm(ALS) for collaborative filtering.
* Predict top 5 artists for a particular user.
* The model evaluation was based on the overlapping of the actual artists list with the predicted artists list.

### Data set
* Audioscrobbler(users-artists and the play counts)

Files
-----

user_artist_data.txt
    3 columns: userid artistid playcount

artist_data.txt
    2 columns: artistid artist_name

artist_alias.txt
    2 columns: badid, goodid
    known incorrectly spelt artists and the correct artist id. 
    you can correct errors in user_artist_data as you read it in using this file
    (we're not yet finished merging this data)

### Reqirements:
* Apache Spark
* Python
* MLLib
* PySpark

### Steps To Run:
* Open Jupyter
```python
jupyter notebook
```
* Open  `recommender.ipynb` in the Jupyter Notebook

#### Ref : http://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html
