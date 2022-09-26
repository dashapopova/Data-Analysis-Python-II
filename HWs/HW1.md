#### Assignment 1 

**due Oct 3rd 23:59**

**Please send a link to your hw folder on github.com to daschapopowa@gmail.com, please check that the repository is open and contains all the files**

**The tasks**

1. Choose a novel or any other long text, e.g., from [http://lib.ru/](http://lib.ru/) and save it in the .txt format. Check that the encoding is UTF-8

2. (2 points) Lemmatize the text using mystem (if you absolutely do not want to use mystem, you can use any other suitable tool we have discussed) and save the result into a .txt file
      
3. (3 points)
    
    - tokenize the text using nltk
    - analyze the words using pymorphy
    - save the results of the analysis in jsonlines (.jsonl): every line contains morphological analysis in a form of a dictionary ```{"lemma": "конь", "word": "коня", "pos": "NOUN"}```

4. (2 points) Answer the following questions:
    
    - What percentage constitutes each pos? (E.g., for the verb, the number of verbs divided by the total number of words)
    - Print out top-20 verbs and adverbs
    - you can keep the stop words or you can get rid of them

5. (1 point) Find top-25 bigrams and trigrams for your text (use nltk.bigrams, e.g.), use only lemmas, get rid of the punctuation. Comment shortly on the results.

6. (2 points) Take 3-8 sentences from the original text and substitute some morphological information, e.g., change the tense of the verbs, the number of the nouns, e.g, the original *Слон подарил мартышке цветы* should become *Слоны подарят мартышкам цветок*.

**Your repository should contain**

1. .ipynb file with the code and comments
2. the .txt file with the text of the book (optional)
3. .txt file with the results of mystem lemmatazation 
4. .jsonl file with the results of the work of pymorphy


