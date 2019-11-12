# TSNE-on-Amazon-Fine-Food-Reviews
Applying State of the Art visualization Technique TSNE on Amazon Fine Food Reviews.

 It is a nonlinear dimensionality reduction technique well-suited for embedding high-dimensional data for visualization in a low-dimensional space of two or three dimensions. Specifically, it models each high-dimensional object by a two- or three-dimensional point in such a way that similar objects are modeled by nearby points and dissimilar objects are modeled by distant points with high probability.
(Source : wikipedia)

Table of Contens:
1. Data Preprocessing :- Data Deduplication, stopward removal, remove special characters, links, HTML tags, numbers etc.
2. Featurization : BOW, TFIDF, Avg Word2Vec, TFIDF Word2Vec.    
3. Applying TSNE on all above given featurizations with various perplexity & n_iter values.
4. Conclusion : There is lot of overlap between positive and negative points. Need to use some other technique for better visualization.
