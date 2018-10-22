# blog-post-clustering
using TfidfVectorizer and KMeans to cluster all my blog posts

My blog (https://www.mindcoolness.com) currently has 322 blog posts, which I have categorized into four broad groups. But wouldn't it be interesting to see how an unsupervised NLP model would cluster them? I think so, which is why I have written this notebook.

Methods: TfidfVectorizer & KMeans

Overview:

    Get Data
    Vectorize Text
    Analyze Clusters
    Compare Predictions
    Plot Results
    Explore Clusters

Required modules: pandas, bs4, sklearn, matplotlib, mpld3
