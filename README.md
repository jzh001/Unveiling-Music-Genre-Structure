# Unveiling music genre structure through common-interest communities

## Abstract
Using a dataset of more than 90,000 metal music reviews written by over 9000 users in a period of 15 years, we analyse the genre structure of metal music with the aid of review text information. We model the relationships between genres using a user-oriented network, based on the written reviews. We then perform community detection and employ a network “averaging” method to obtain stable genre clusters, in order to analyse the structures of clusters both locally within each cluster and globally over the entire network. In addition to identifying the clusters, we use Dependency Parsing and modified Term Frequency–Inverse Document Frequency to extract significant and unique features of each cluster. These structures and review text information can allow us to understand how music audience (fans) perceive similar and different genres, and also assist in classifying different genres which share common-interest user communities, offering a more objective way in grouping music genres. Furthermore, the classification can also help recommendation engines provide more targeted suggestions of music, and potentially help musicians to select genre labels for their music, and design music to better cater to preferences of their audiences based on previous reviews.

Paper: https://link.springer.com/article/10.1007/s13278-022-00863-2

## Note to reader:

The Jupyter Notebook labelled "Network of Genres.ipynb" was used in our paper to generate the network of genres. 



## Data
The data used for the notebook was obtained from Encyclopedia Metallum (https://www.metal-archives.com), and was preprocessed using the dependency parsing method as illustrated in our paper, before generating the eventual genre network. The data provided in this repository (user_genre_data.csv) is a subsegment of the overall data used, where only the user, list of genres and review score are provided. 
