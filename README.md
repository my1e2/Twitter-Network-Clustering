# Twitter-Network-Clustering

Write a Medium post on constructing and characterizing clusters in a given dataset. Using methods from module 4, you should construct a dataset of interest, select (and justify) a k value for the number clusters in your data, cluster your data using one of the methods we've discussed, and then describe what you think these clusters represent. As in the previous assignment, you may use any distance/similarity metric you like, but note that your choice of metric impacts which clustering metric you use.

Your post should include the following:

Describe a question you think can be answered using network data, what specific stakeholder is asking this question, and what decision(s) the answer to this question will inform.

Describe the data that could answer this question, what fields it contains, and why it is relevant to your question.

Explain how you collected some subset of this data (e.g., libraries like requests, BeautifulSoup, tweepy, praw, etc. or from data archive).

Define how you are measuring similarity between data points; include what features you are using for measuring similarity.

Discuss how you selected a value for k, the number of clusters (e.g., thresholding, pre-defined, etc.).

Describe what you think each cluster in your dataset represents or describes (e.g., by looking at the messages/documents/items/users in each cluster), giving an example of at least two elements in each cluster.

Provide an answer to your question, explaining your analysis of the data you collected, and how it answers that question.

Include figures or tables summarizing your findings. 

Discuss the limitations of your analysis. What’s missing? How might it be biased?

For simplicity, scikit-learn has implementations for several clustering approaches we can use:

K-Means (Links to an external site.), with Euclidean distance, 
Agglomerative Cluster (Links to an external site.), with Euclidean or cosine or a some pre-computed (e.g., Jaccard) distance, and
Other general clustering (Links to an external site.) approaches
