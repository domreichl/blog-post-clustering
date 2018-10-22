# blog-post-clustering
using TfidfVectorizer and KMeans to cluster all my blog posts

My blog (https://www.mindcoolness.com) currently has 322 blog posts, which I have categorized into four broad groups. But wouldn't it be interesting to see how an unsupervised NLP model would cluster them? I think so, which is why I have written this notebook.

Overview:
1. Get data
2. Vectorize text
3. Analyze clusters
4. Compare predictions
5. Plot results

Methods: TfidfVectorizer & KMeans

Required modules: pandas, bs4, sklearn, matplotlib, mpld3
