# nlp-research
## Getting Started with NLP using NLTK

### Reference Guide : https://nlpforhackers.io/start/

#### Notebook 1:
- Gender-Classification on Names using a Decision Tree
- Resource on Normalizing Data : http://simpledatamining.blogspot.com/2015/05/how-to-deal-with-mixed-data-types-when.html
  1. numerical data   --> normalize
  2. categorical data --> one-hot encoding
  3. ordinal data     --> normalize without one-hot encoding

#### Notebook 2:
- Model to build a simple inverted indexing for input sentences using NLTK (tokenization + stopword-removal + stemming/lemmatization)
- Resource on Stemming vs Lemmatization : https://nlp.stanford.edu/IR-book/html/htmledition/stemming-and-lemmatization-1.html

#### Notebook 3:
- Text Classification of a News Corpus using different methods to vectorize the given input
- Resource explaining the different ways to vectorize text : https://monkeylearn.com/blog/beginners-guide-text-vectorization/
- Possible Representations :  
  1. tf.idf
  2. word2vec
  3. skip-thought-vectors (Not Implemented)

#### Notebook 4:
- Train custom NER tagger using spaCy to extract Aspects and Entities from given text corpus 