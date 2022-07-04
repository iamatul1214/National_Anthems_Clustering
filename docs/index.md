# National Anthem Clustering Project Documentation
 National Anthem clustering

## STEPS -

### STEP 01- Create a repository by using template repository

### STEP 02- Clone the new repository

### STEP 03- Create a conda environment after opening the repository in VSCODE

```bash
conda create --prefix ./env python=3.7 -y
```

```bash
conda activate ./env
```
OR
```bash
source activate ./env
```

### STEP 04- install the requirements
```bash
pip install -r requirements.txt
```

### STEP 06- commit and push the changes to the remote repository


## Steps used in this project

### 1. Explore our collection of national anthems (corpus)
### 2. Data Engineer the dataset to get the best perfomance from the K-means algorit hm
### 3. Run the algorithm many times, each time testing with a different number of clusters
### 4. Use different metrics to visualize our results and find the best number of clusters (ie. Why are a total of X clusters better than a total of Y clusters)
### 5. Cluster Analysis

## Metrics Utilized for Determining the Best Number of K Cluters:

### Elbow Method
### Silhouette Score


### Importing the libraries
```bash
# data structures
import pandas as pd
import numpy as np
# import geopandas as gpd
import json

# Corpus processing
import re
import nltk.corpus
from unidecode import unidecode
from nltk.tokenize import word_tokenize
from nltk import SnowballStemmer
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.preprocessing import normalize

# clustering
from sklearn import cluster

# visualization
import matplotlib.pyplot as plt
import matplotlib.cm as cm
import seaborn as sns
from sklearn.metrics import silhouette_samples, silhouette_score
from wordcloud import WordCloud

# Map visualization
import folium
from branca.element import Figure
```

## word clouds formed from dataset of national anthems
### Common words of cluster 0
![alt text](https://github.com/iamatul1214/National_Anthems_Clustering/blob/main/Images/wordclouds/cluster__0.png "common words in cluster 1")
