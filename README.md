# clustering_spotify

Problem definition: 
Examine a set of audio_features of songs and using clustering techniques identify potential genres.
The goal is define genres and their characteristics.

## 1.1 Explore the data
Data file contains 6171 rows and 9 features
THe songs were extracted using spotify API 
search year:1994
search year:2000
search year:2001
artist from different genres

## 1.2 Choose algorithms
I used three different type of clustering:
- K-Means clustering
- Agglomerative clustering
- Density based clustering

## 1.3 Dimentionality Reduction and Visualization

- PCA
- TSNE

# Clustering audio tracks and compare with existing genres

Problem definition: 
Created segmentation on dataset of audio tracks for the year 1996.
Extracted artists genres to compare results.

# Results:

After clustering analysis and visualization I got a rough idea of audio track genres that were in 1996. I was able to identify only four clusters: Classical, Pop, Rock, Jazz.

I checked my results by extracting artists genres of the audio tracks from 1996. The most common genres were defined by grouping of music type. Pop, Rock, Folk, Dance, Metal and Classical

In the plot, that provided spotify there is a significant difference only for Classical music  (low: danceability, energy) and some Rock music (lower: acousticness)

Popular music in the 1990s (wiki): The Red Hot Chili Peppers, Nirvana, No Doubt, Green Day, The Offspring, Marilyn Manson, Aerosmith, Bon Jovi,Backstreet Boys, *NSYNC, Christina Aguilera, Britney Spears, Jennifer Lopez and Destiny's Child, Michael Jackson





