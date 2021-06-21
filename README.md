## Psychological Counselling Information Retrieval

#### This application is designed to retrieve information about similar cases and episodes given the user (therapist) knows a few details about the patient. The information retrieved will be cases similar to the patient and can help the therapist treat him/her better and also help the therapist in how to go about new and uncertain cases. The therapist can also use this search engine if he/she would like to volunteer to help other patients who are in need and cannot afford a therapist.

#### 
[Design Doc](https://docs.google.com/document/d/1VgWjNgLPa2f-xUXzArxnN3hKYnhJVxk64PtsIyAEVUY/edit?usp=sharing)

### Requirements

*Python 3.6
*Jupyter Notebooks
*Google's Fake News Word Embedding
*nltk : pip install nltk
*pickle : pip install pickle
*re : pip install regex
*numpy : pip install regex
*itertools : pip install more-itertools

### Run

Open all the files in Google Colaboratory or Jupyter Notebooks
1. Run Steps 2 and 3 only for the first time

2. Run all the cells in the Preprocessing.py. The script builds the inverted index and stores it in the same directory.
3. Run WordEmbedding.py to use the word2vec model which calculates the similarity scores of all the unique words in the dataset
4. Run Search.py and to search for keyword(s) which will return the top 10 relevant documents
