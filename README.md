# MIT_AI_Studio
An AI Application in Business
--- Topic Modeling for Online Product Review

In the term of 2024-25 
For the Tech AI Challenge of MIT Schwarzman College of Computing

Challenge title: Topic Modeling for Online Product Review
Industry: Businesses in retail, hospitality, banking, and other consumer-service industries that collect online feedback on services and products, such as Amazon, Target, Expedia, Marriott, and Bank of America
Machine Learning Problem Type: Clustering with Large Language Model (LLM)

Challenge description: 
Context / Impact:
The study of online product reviews provides a wealth of information that can be leveraged across various aspects of retail business operations. The product reviews reveal consumer’s preference on product attributes, helping the e-commerce in competitive analysis, product development, and design marketing strategies. Moreover, product reviews influence other customer’s purchase decisions, therefore, it is important for the retailer to learn insights to earn customer trust and loyalty and improve quality control. 

Challenge Summary:
The goal is to build a topic model with a Large Language Model (LLM). Product reviews are textual, which can’t be used by traditional machine learning approaches. LLM which converts textual data into numeric representations, can be used to model a series of unstructured data. 

Approach
The model pipeline can be generalized as below steps:

Step 1: Convert product reviews to LLM embeddings.
Step 2: Cluster product reviews based on their corresponding LLM embeddings.
Step 3: Generate labels for each cluster.

Choices of LLMs: llama2, BERT, Sentence Transformer
Choices of clustering: HDBSCAN, K-means

Dataset description: The dataset consists of samples from Amazon Ratings for selected products in csv format. The reviews are picked randomly, and the corpus has nearly 1.6k reviews of different customers. The dataset was uploaded to Kaggle, a publicly shared database, for research purposes. 

Data location: https://www.kaggle.com/datasets/yasserh/amazon-product-reviews-dataset

References: 
https://cseweb.ucsd.edu/~jmcauley/datasets.html#amazon_reviews
https://www.kaggle.com/datasets/yasserh/amazon-product-reviews-dataset/code
https://www.kaggle.com/code/jacopoferretti/amazon-reviews-topic-class-w-bertopic-clusters
https://blog.lmorchard.com/2024/05/10/topic-clustering-llamafile/#vector-embeddings-ala-llamafile
