# Law Recommendation System 
We used two 
## Version1: Using TF-IDF
**STEP**
1. Add new text(do some preprocessing) in tf-idf matrix
2. Calculate new cosine similarity
3. Find top 10 similar text using Cosine Similarity
4. Show top 10 similar texts and the law corresponding to those texts

## Version2: Using TF-IDF Weighted Word2Vec
**STEP**
1. Create TF-IDF
2. Convert a tf-idf dictionary with word as key, idf as a value
3. Get TF-IDF features
4. Create Word2Vec Model
5. Combine w2v with TF-IDF
6. Find top 10 similar text using Cosine Similarity
7. Show top 10 similar texts and the law corresponding to those texts
