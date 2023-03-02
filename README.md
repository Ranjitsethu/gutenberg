# Clustering (Group Assignment 2)
## About the project
The objective of this project is to classify five different books of different authors that are sementically similar and create 200 documents of each book where each document has a total of 150 words. We created labels for each words and transformed these words into BOW, TF-IDF and LDA. We also used K-means, ARI and EM algorithms to compare the best model and the evaluation is done by using coherence, kappa and Silhouette and visualised the results obtained using the graphs
## Built with
This project was created using the Python programming language and a variety of Python data frames, including numpy, pandas, and others.
##  About Coding part
i) Choosing data of our choice and labelling the data

  First of all we import all the packages required for this function and then we get the samples of 5 gutenberg digital books which are of different authors and different genre and we give labels to each word obtained from the book.
  
ii) Preprocessing and data cleaning

 Here the data obtained from the samples is preprocessed and cleaned. We removed all the stopwords and unwanted characters and the words which are of two letters or less were also removed  by using the concepts of lemmatization and stemming for more accuracy.
 
iii) Feature Engineering

After preprocessing and cleaning the data it is represented in various forms such as Bag of words where the frequency of each word is alone considered  and TF-IDF where the importance of each word is taken into account.
  
iv) Usage of different Machine learning models

Here we use different clustering algorithms like K-means and ARI and EM algorithms to work on the data obtained after cleaning the samples of the book.
    
v) Evaluations

Now we run the above code and evaluate the performance of the model by the obtained results for K- means, ARI and EM algorithms and decide which is the best clustering algorithm by visually plotting the data obtained from these results
    
vi) Deciding which algorithm is best

After checking the performance of each model we concluded that for our data the K-means model has outperformed all the other models which made us conclude that K-means is the best model of all the models used.
    



