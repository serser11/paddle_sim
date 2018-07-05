Used both gensim and paddlepaddle packages to implement word2vec and calculate similarity between words. Can also be used as tag matching algorithm for matching each user's query with most possible 20 results.

wordseg.so : package for segmenting Chinese words and phrases.

read.py : implemented to segment words and store in another directory for preparation. This step could be neglected or used as a test to see the result of wordseg.so.

process.py : simple example for training gensim model.

use.py : implemented with gensim. Can be directly used to run on data text. Will show: query followed by top 10 most similar tags.

use_paddle.py : implemented with paddlepaddle. Can be directly used to run on data text. Will show: query followed by top 10 most similar tags.


