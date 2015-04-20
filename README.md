# Search-Engine-learn-to-ranking

1. For a query, we use a lot of approaches to retrieve the data: BM25, Indri, Vector Space
2. Different approaches combined to improve accuracy
3. For query q, model document d as x=f(q,d)-> x is the feature vector of q and d
4. PointWise approach to train data:For documents, there is a document score!
   Maybe solution:
    train data: query q, document d1, score1
    Step1: retrieve feature vector of f(q,d1)
    Step2: Use SVM to train the data


April 19:
1. PageRankIndex: there are two solution:1. read in and store in local and search
                                         2. read as you search
                  Choose the first way as you search a lot

2. How to implement Indri part?: it spends me a lot of time!
    
3. TermOverlap : Basically, you go through the query terms and count the number of terms that match the document (by going through the stems from the term vector).
The term overlap will be the number of terms that match the document divided by the total number of query terms.
4. Problem: java heap : xmx- 2g
