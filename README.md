# extractive-text-summarizer
The repository deals with the tool which provides summary of an article.
The technique used here is called extractive text summary. The model first cleans an article by removing stopwords, tokenizes the words. Then it finds simliarity between the words by converting them into vectors and finding the cosine similaerity between them.
Eventually, the model finds TF-IDF score for each sentence. In simple terms, the TF-IDF score tells us the importance of a sentence in the article based on the frequency of occurence of the words in the sentence in the article. Then the tool gives a summary of a fixed length, thus saving user's time. 
