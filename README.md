# Clustering-Method
Clustering methods are used to identify groups of similar objects in a multivariate data sets collected from fields. In this project, k-means cluster, hierarchical cluster, and spectral cluster are provided in the sample code.

# Dataset

![image](https://user-images.githubusercontent.com/95513386/146653351-a4be3334-4b56-4b1b-b76d-bdf26f6d49d0.png)


We crawled articles in different areas of Wikipedia. The topics of these articles form a hierarchy (given by Wikipedia), as shown
in Figure 1. We selected 10 documents in each of the finest topic categories (leaf nodes in the figure). We
provide you the documents in a featurized form.

Each document has undergone the following pre-proessing steps:
1. Removal of links, formulas, tables, reference lists, and media other than text.
2. Removal of certain words. These words include “stop words” that do not convey significant meaning,
such as “a”, “the”, “me”, and digits (for purpose of controlling the vocabulary size).
3. Stemming, where the affixes of each word are removed and only the remaining stem is retained. The
vocabulary size (number of unique word types) in the dataset is 9,729 after pre-processing.
  
