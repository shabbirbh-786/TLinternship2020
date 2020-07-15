
## Model Building for Clustering

### Data Cleaning
- cleaned the content of website by following steps
 1. Removed stop words as they doesn't added any specific meaning to the text.
 2. Removed punctuation
 3. Did the text normalization by lemmatizing the words.
 
### Data vectorization
- Converted the sentences into the TF-IDF using vectorizer
- This will help in computing the similarity between the sentences for the model
- Save the vectorizer if in future we want to use it for a classification purpose

### Built a model
- Then built a kMeans model out of it with the specified number of cluster which will classify the unlabel data into the clusters depending on its neighbouring sentences label
- we have divided URL into two clusters one which will support the hydroxychloroquine for COVID and one which doesn't using this model.
- Then we will save all the URL into a list which belong to the cluster which supports the hydroxychloroquine use for COVID-19.


