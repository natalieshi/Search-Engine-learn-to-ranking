# Search-Engine-learn-to-ranking

1. For a query, we use a lot of approaches to retrieve the data: BM25, Indri, Vector Space
2. Different approaches combined to improve accuracy
3. For query q, model document d as x=f(q,d)-> x is the feature vector of q and d
4. PointWise approach to train data:For documents, there is a document score!
   Maybe solution:
    train data: query q, document d1, score1
    Step1: retrieve feature vector of f(q,d1)
    Step2: Use SVM to train the data
