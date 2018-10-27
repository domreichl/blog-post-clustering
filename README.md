# blog-post-clustering

## Part 1

My blog (https://www.mindcoolness.com) currently has 322 blog posts, which I have categorized into four broad topics. As I think it would be interesting to see how an unsupervised NLP model would cluster them, I have written this notebook.

Overview:
1. Get data
2. Vectorize text
3. Analyze clusters
4. Compare predictions
5. Plot results
6. Explore clusters

To see the output of #6 and use the interactive plot, please visit https://nbviewer.jupyter.org/github/domreichl/blog-post-clustering/blob/master/bp_clustering.ipynb.

## Part 2

In Part 1, I used KMeans to cluster the corpus of my blog, analyzed some model predictions, and visualized my data. In this part, I want to compare 4 different models (KMeans, NMF, LSA, LDA) and 3 model combinations (NMF-based KMeans, LSA-based KMeans, LDA-based Kmeans) and evaluate them both qualitatively and quantitatively.

Overview:
1. Modules & Data
2. Vectorization
3. Word Frequency
4. Models & Model Combinations
5. Qualitative Evaluation
6. Quantitative Evaluation

## Part 3

In Part 3, which will be the last part for now, I use TensorFlow to build an autoencoder for clustering.

Overview:
1. Modules & Data
2. Vectorization
3. Autoencoder
4. Evaluation
5. Conclusion
