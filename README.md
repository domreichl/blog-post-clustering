# blog-post-clustering
using TfidfVectorizer and KMeans to cluster all my blog posts

My blog (https://www.mindcoolness.com) currently has 322 blog posts, which I have categorized into four broad topics. As I think it would be interesting to see how an unsupervised NLP model would cluster them, I have written this notebook.

Overview:
1. Get data
2. Vectorize text
3. Analyze clusters
4. Compare predictions
5. Plot results
6. Explore clusters

To see the output of #6 and use the interactive plot, please visit https://nbviewer.jupyter.org/github/domreichl/blog-post-clustering/blob/master/bp_clustering.ipynb.

Methods: TfidfVectorizer & KMeans

Required modules: pandas, bs4, sklearn, matplotlib, mpld3
