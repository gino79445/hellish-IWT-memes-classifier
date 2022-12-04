# hellish-IWT-memes-classifier
## the models  
+ **The first model:** the model of classifying into IWT-meme and non-IWT-meme.

+ **The second model:** the model of classifying into non-hellish IWT-memes and hellish IWT-memes.( text feature vectors obtained from word2vec)

+ **The third model:** the model of classifying into non-hellish IWT-memes and hellish IWT-memes.( text feature vectors obtained from BERT)

## The folders  
***context _ bert _ meme*** containing the text feature vectors obtained from Bert, which is used to train the fisrt model. 

***w2c_context*** containing the text feature vectors obtained from word2vec, which is used to train the second model. 

***context _ bert _ hell*** containing the text feature vectors obtained from Bert, which is used to train the third model. 

***meme_npy_val*** containing the data used to train and validate the first model.

***w2c_npy_val*** containing the data used to train and validate the second model.

***hell_npy_val*** containing the data used to train and validate the third model.


## Run
You have to make the antlr-3.5.2-complete.jar and makefile in current folder and the environment of java has been installed,and run the following command:  
(*if you want to generate test1.c immediate code*)
```shell
make 
java -cp ./antlr-3.5.2-complete.jar:. myCompiler_test test1.c >> test1.ll
```
or  
```shell
java -cp ./antlr-3.5.2-complete.jar org.antlr.Tool myCompiler.g
javac -cp ./antlr-3.5.2-complete.jar:. *.java
java -cp ./antlr-3.5.2-complete.jar:. myCompiler_test test1.c >> test1.ll
```
