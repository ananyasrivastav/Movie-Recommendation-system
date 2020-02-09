# Movie-Recommendation-system
Using Sklearn Library
TF-IDF means “Term Frequency - Inverse Document Frequency”. This is a technique to count words in documents, we generally assign a weight to each word which signifies the importance of the word in the corpus(document). This method is a mostly used in Information Retrieval and Text Mining.
If suppose, for example “This building is tall”. It is easy for us to understand the sentence as we know the semantics of the words and the sentence. But how can a  computer understand this sentence? The computer can understand any data of the form  numerical value. So,this is the reason that we vectorize all the text so that the computer understands the text better.
By vectorizing the documents we can further perform multiple tasks such as finding the relevant documents, ranking, clustering and so on. This is the same thing that happens when you perform a google search. The web pages are called documents and the search text with which you search is called a query. google maintains a fixed representation for all of the documents. When you search with a query, google will find the relevance of the query with all of the documents, ranks them in the order of relevance then shows the top n documents, which is done using the vectorized form of query and documents. 
So, our TF-IDF,
TF-IDF = Term Frequency  * Inverse Document Frequency 
Terminology
t — term (word)
d — document (set of words)
N — count of corpus
corpus — the total document set
Term Frequency
