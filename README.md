# Content-based Recommender System for Taipei Public Works Department
Public Link for the prject: http://d4sg.org/smart-audit/

## Problem Statement
Taipei PWD(Public Works Department) asked auditors to submit illegal cases during their audit. The problem is, auditors often submit illegal cases with wrong corresponding law, so the staff in PWD need to spend lots of time check their files and adjust wrong laws.
Therefore, they asked us to design a law recommender system for auditors. When auditors are entering illegal cases, the system will automatedly recommend appropriate law for them.

## How to Do
We create a law recommendation system using simply TF-IDF and TF-IDF Weighted Word2vec to improve the procurement efficiency of Public Works Department in Taipei City Government.

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

## Version3: Using TF-IDF Weighted Words Embedding with Pretrained Words Embedding
**STEP**
1. Create TF-IDF
2. Convert a tf-idf dictionary with word as key, idf as a value
3. Get TF-IDF features
4. Combine pretrained words embedding with TF-IDF
5. Calculate Cosine Similarity
6. Recommend Law


Finally, we use the third model for its efficiency. If you want to see more information, you can check this link for the complete task.
