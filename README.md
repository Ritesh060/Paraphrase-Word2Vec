# Paraphrase-Word2Vec
 A program to paraphrase a given sentence by finding out similar words using a model trained using Word2Vec model.

## Dataset 

Dataset used here is [Wikipedia Sentences](https://www.kaggle.com/datasets/mikeortman/wikipedia-sentences). This dataset is used because it has 7.8 million sentences which is ample data to make a model with good results. Also, it has sentences which gives words context, which helps in forming better vector for each word in dataset according to the technique being used.

## Language Model 

The language model used here is N-Gram.

An n-gram model is a type of probabilistic language model used in natural language processing and computational linguistics. It predicts the probability of a word based 
on the previous n-1 words in a given text or corpus. The model is based on the assumption that the probability of a word is dependent on the probability of the preceding 
n-1 words, and that the probability of a longer sequence of words can be decomposed into the product of the probabilities of the individual n-grams. N-grams can be 
unigrams (single words), bigrams (pairs of adjacent words), trigrams (triplets of adjacent words), or higher order n-grams. The n-gram model is widely used in various 
applications, such as speech recognition, machine translation, and text classification.

## How to run this model?
To run this model first, first download the dataset and the repository.

Then make the model files using [main.ipynb](https://github.com/Ritesh060/Paraphrase-Word2Vec/blob/main/main.ipynb).

It takes around 4 hours to make the required model files.

Then run [paraphrase_main.ipynb](https://github.com/Ritesh060/Paraphrase-Word2Vec/blob/main/paraphrase_main.ipynb), to input the sentence to be paraphrased.
