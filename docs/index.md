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