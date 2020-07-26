# RECOMMENDER SYSTEM - Similar Movie Identification

In this project, 

The SIMILAR MOVIE IDENTIFICATION SYSTEM is developed at the aim of finding out the most similar movie match using Natural Language Processing techniques. This implementation that aids in identification of similar movie will help in constructing more precise recommender systems. The system is built using the libraries from scikit-learn and NLTK by utilizing the plot summary data of various movies from wikipedia and IMDb data.

## NATURAL LANGUAGE PROCESSING
Natural language processing (NLP) describes the interaction between human language and computers. It is a collective term that refers to automatic computational processing of human languages. This includes both algorithms that take human-produced text as input, and algorithms that produce natural looking text as outputs.


Some everyday uses of nlp are:
* Spell check


* Autocomplete


* Voice text messaging


* Spam filters


* Related keywords on search engines


* Siri, Alexa, or Google Assistant


## KEY CONCEPTS USED IN THIS PROJECT

### 1. Tokenization
Tokenization is the task of chopping it up a character sequence into pieces, called tokens , perhaps at the same time throwing away certain characters, such as punctuation. These tokens are very useful for finding patterns as well as is considered as a base step for stemming and lemmatization.

For example: The sentence “ How are you? ” can be splitted into the tokens “how”, “are”, “you”. 


### 2. Stemming 
Stemming is the process of reducing inflected (or sometimes derived) words to their word stem, base or root form—generally a written word form. A computer program or subroutine that stems word may be called a stemming program, stemming algorithm, or stemmer. In precise, Stemming helps in the reduction of the words to a compact form called word stem.

For example: “Flying” is a word and its suffix is “ing”, if we remove “ing” from “Flying” then we will get base word or root word which is “Fly”. We uses these suffix to create a new word from original stem word.

The three major stemming algorithms that are in use today are 
  * **Porter** : Most commonly used stemmer without a doubt, also one of the most gentle stemmers. It is also the most computationally intensive of the algorithms(Granted not by a very significant margin) and the oldest stemming algorithm by a large margin.
  
  
* **Snowball** : Nearly universally regarded as an improvement over porter, and for good reason. Porter himself in fact admits that it is better than his original algorithm. Slightly faster computation time than porter, with a fairly large community around it.


* **Lancaster** : Very aggressive stemming algorithm, sometimes to a fault. With porter and snowball, the stemmed representations are usually fairly intuitive to a reader, not so with Lancaster, as many shorter words will become totally obfuscated. The fastest algorithm here, and will reduce your working set of words hugely, but if you want more distinction, not the tool you would want.

In this project, we have used the Snowball stemmer. There are certain circumstances in which Lancaster algorithm can hugely trim down the working set of data, which can be very useful, however the marginal speed increase is worth.



### 3. Count Vectorizer
The Count Vectorizer provides a simple way to both tokenize a collection of text documents and build a vocabulary of known words, but also to encode new documents using that vocabulary. In short, Convert a collection of text documents to a matrix of token counts.

**Parameters**:

   * Stop Words

  * ngram_range

  * min_df and max_df

  * max_features

### 4. TF-IDF Vectorizer
TF-IDF Vectorizer converts the text documents to a matrix of "tfidf" features. tfidf features are the method to convert the textual information into the vector space, they are a measure of how important a word in a text is.

**tf-idf(t, d) = tf(t, d) * log(N/(df + 1))**

  
### 5. Cosine Similarity 
Cosine similarity is a metric used to determine how similar the documents are irrespective of their size. When plotted on a multi-dimensional space, where each dimension corresponds to a word in the document, the cosine similarity captures the orientation (the angle) of the documents and not the magnitude.


### 6. Dendrogram
A dendrogram is a diagram that shows the hierarchical relationship between objects. It is most commonly created as an output from hierarchical clustering. The main use of a dendrogram is to work out the best way to allocate objects to clusters.


## Note
Kindly do not try to reciprocate the implementaion as it is my unique work. Incase, If you would like to improve or make productive changes to the code, kindly pull request or notify me.

**THANK YOU**
