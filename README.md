# Search-Engine-for-Movie-Plot-Summaries
Build a Search Engine for movie plot summaries using tf-idf technique in MapReduce

Steps:
1. Upload the movie summaries file 'plot_summaries.txt' Databricks.
2. remove stopwords by using NLTK Stopword Library.
3. Create a tf-idf for every term and every document using the MapReduce method in PySpark.
4. Read the search terms from user and output following:
(a) User enters a single term: output the top 10 documents with the highest tf-idf values for that term.
(b) User enters a query consisting of multiple terms: evaluate cosine similarity between the query and all the documents and return top 10 documents having the highest cosine similarity values.
5. Return the list of movie names sorted by their relevance values in descending order by using the 'movie.metadata.tsv' file to lookup the movie names.

