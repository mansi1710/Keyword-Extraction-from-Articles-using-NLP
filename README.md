# Keyword-Extraction-from-Articles-using-NLP

Extracting keywords for articles using Natural Language Processing techniques.

## Dataset:

The dataset used for the project is from Kaggle- NIPS Papers. 
https://www.kaggle.com/benhamner/nips-papers/home

Neural Information Processing Systems (NIPS) is one of the top machine learning conferences in the world. This dataset includes the title and abstracts for all NIPS papers to date (ranging from the first 1987 conference to the current 2016 conference).

## Approach

![alt text](https://cdn-images-1.medium.com/max/1000/1*i8wBs9pOAaC0QlBz2ql9Ug.png)

**Text pre-processing** can be divided into two broad categories — noise removal & normalization.

Data components that are redundant to the core text analytics can be considered as **noise**.

**Sparsity**: In text mining, huge matrices are created based on word frequencies with many cells having zero values. This problem is called sparsity and is minimized using various techniques.

# Text Pre-Processing

!["Text Pre-Processing"](https://cdn-images-1.medium.com/max/1000/1*yOna3oFFjHmCRti1qusMAA.png)

Handling multiple occurrences / representations of the same word is called **normalization**. 

There are two types of normalization 

-  stemming and 
-  lemmatization.

**Stemming** normalizes text by removing suffixes.

**Lemmatisation** is a more advanced technique which works based on the root of the word.

![alt text](https://cdn-images-1.medium.com/max/1000/1*vwT-_4Eo5vcNrQ9JNl1gYg.png)
