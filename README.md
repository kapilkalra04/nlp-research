# nlp-research
## Getting Started with NLP using NLTK

### Reference Guide : https://nlpforhackers.io/start/

#### Notebook 1 (dir: gender-classifier-names):
- Gender-Classification on Names using a Decision Tree
- Resource on Normalizing Data : http://simpledatamining.blogspot.com/2015/05/how-to-deal-with-mixed-data-types-when.html
  1. numerical data   --> normalize
  2. categorical data --> one-hot encoding
  3. ordinal data     --> normalize without one-hot encoding

#### Notebook 2 (dir: nltk-inverted-indexing):
- Model to build a simple inverted indexing for input sentences using NLTK (tokenization + stopword-removal + stemming/lemmatization)
- Resource on Stemming vs Lemmatization : https://nlp.stanford.edu/IR-book/html/htmledition/stemming-and-lemmatization-1.html

#### Notebook 3 (dir: text-classification):
- Text Classification of a News Corpus using different methods to vectorize the given input
- Resource explaining the different ways to vectorize text : https://monkeylearn.com/blog/beginners-guide-text-vectorization/
- Possible Representations :  
  1. tf.idf
  2. word2vec (Not Implemented)
  3. skip-thought-vectors (Not Implemented)

#### Notebook 4 (dir: word2vec):
- Create a custom word2vec library based on the OpinRank dataset containing reviews about cars and hotels 
- Reference Article : http://kavita-ganesan.com/gensim-word2vec-tutorial-starter-code/#.XBjfIWloTDc
- Dataset: https://github.com/kavgan/nlp-text-mining-working-examples/tree/master/word2vec