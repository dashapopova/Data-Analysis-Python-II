#### Assignment 1 -- due Sept 24th -- please send a link to your hw folder on github.com to daschapopowa@gmail.com

1. Choose a long text (a novel), do preprocessing on it (delete punctuation, lemmatize it, make sure that every sentence starts on a new line), don't forget to put the lemmatized text or a link to your lemmatized text into your hw folder -- 1 point
2. Train a word2vec model on the chosen text, set the parameters (window size, vector size, number of iterations etc.), comment on your choice of parameter settings and the reasoning behind it, experiment with the settings and show me that you have chosen the settings after some experimentation and consideration -- 2 points 
3. Test your model, use `most_similar`, `similarity`, `doesnt_match` functions, comment on the model performance, explain the reasoning behind the testing -- 2 points 
4. Visualize the results of the training and testing (one plot or one graph), comment on the visualization -- 1 point
5. Choose two sentences from the original text and substitute all the meaningful words with their closest neighbours from your word2vec model (1 point), do the agreement on the sentences with substitutions (1 point)

If you want to get a 9, do all of the above plus provide an additional visualization that uses a different method of dimension reduction (not PCA), comment on the differences between using PCA on your dataset and the other method of dimension reduction.

If you want to get a 10, do all of the above plus provide a BERT or an ELMO model for your data, comment on the differences in the results between the word2vec and the BERT/ELMO models.
