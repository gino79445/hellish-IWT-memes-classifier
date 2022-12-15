# hellish-IWT-memes-classifier
## the models  
+ **The first model:** the model of classifying into IWT-meme and non-IWT-meme.

+ **The second model:** the model of classifying into non-hellish IWT-memes and hellish IWT-memes.( text feature vectors obtained from word2vec)

+ **The third model:** the model of classifying into non-hellish IWT-memes and hellish IWT-memes.( text feature vectors obtained from BERT)

## The folders  
***context _ bert _ meme***(incomplete) containing the text feature vectors obtained from Bert, which is used to train the fisrt model. 

***w2c_context***(incomplete) containing the text feature vectors obtained from word2vec, which is used to train the second model. 

***context _ bert _ hell***(incomplete) containing the text feature vectors obtained from Bert, which is used to train the third model. 

***meme_npy_val*** containing the data used to train and validate the first model.

***w2c_npy_val*** containing the data used to train and validate the second model.

***hell_npy_val*** containing the data used to train and validate the third model.

## code
***meme_class.ipynb***: training the first model.


***hell_class_w2c.ipynb***: training the second model.


***hell_class.ipynb***: training the third model.


***hell_meme_cont_bert.ipynb***: generating  ***context _ bert _ hell***


***meme_cont_bert.ipynb***: generating  ***context _ bert _ meme***


