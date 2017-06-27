# Language-Model
Natural Language Processing Model used for Word Prediction
## Word Prediction
N-grams used to predict the most likely word after an input text.
- Used dictionary of dictionary to implement probability and prediction table of n-grams
- Dataset:
  + 1.9 million training corpus
  + Testing corpus formed by partitioning training corpus in 9:1 ratio
  + Testing corpus partitioned in 1:1 ratio to create held-out  corpus
## Smoothing
Three methods of smoothing has been used in our model:
* Add K Smoothing
* Good Turing Smoothing
* Kneser Ney Smoothing
## Interpolation
Simple interpolation procedure. Parameters have been tuned from held set using:
* Grid Search
* Random Search
## Backoff
Backoff methods used for prediction as well.
## Perplexity
Perplexity calculation done to evaluate the performance of the model

