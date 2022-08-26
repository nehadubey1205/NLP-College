# NLP-college
#I am using for college assignment.
#Assignment-1

1-Word and Sentence Tokenization: Write a python program that reads text from an input file (use your own input text file, refer the sample input file below, if you are using google colab then learn how google colab can read an input file) and counts the number of sentences and words. And the program outputs the frequency of each word. (Use dictionary data-structure to solve it, create an input file as given below). Do not use NLTK library function. [2 pts]
 	
2-Stop word removal: Write a python program that reads text from an input file, and removes all the stop words and prints the output text without stop words. Prepare your own list of stop words (you can have 5-6 stop words in your list). Do not use NLTK library function. [2 pts]

3-Stemming: Write a python program that uses NLTK library to run porter stemmer. [2 pts]

4-Lemmatization: Write a python program that uses NLTK library to lemmatize a given input word. [2 pts]

5-POS Tagging: Write a python program that uses NLTK library to perform POS tagging in a given input sentence. [2 pts]
#Assignment-2
#Attempt all the questions in this assignment in a single jupyter notebook (use google colab). Your outputs should be visible in the notebook. Save the notebook as a single ipynb file and submit it on google classroom.
Dataset (D1): This is a textual dataset comprising of user generated text (there are many examples of user generated text, like social media posts, review comments, etc)
https://drive.google.com/file/d/1H7xOPBH5n92GCrbeMpaj_KBzDwnBsBv_/view?usp=sharing	

Perform the following tasks on Dataset (D1).
For each row of the ‘content’ attribute, find length of content, number of punctuations, number of stopwords, and number of times ‘@’ appears in the tweet text. Save these values into four new columns, name them as ‘length’, ‘punct’, ‘stopwords’, and ‘mentions’.
Draw correlation plot and find if any correlation exists between the ‘sentiment’ attribute with these four new columns (also known as features). You would be required to encode the ‘sentiment’ attribute. Interpret the correlation values as comments.
Remove stopwords, and then tokenize words in each row of the ‘content’, count the number of words, and save into a new attribute ‘wordCount’. Use the NLTK library.
Draw separate word clouds for each of the following sentiment values: sadness, enthusiasm, and neutral. Write your observations as comments.

2. Perform the following on Dataset (D1).
Perform two approaches of pre-processing (P1) include @ mentions, (P2) remove @ mentions; Call the pre-processed datasets as D2 and D3, respectively. 

After pre-processing each of the above approaches, you need to convert the sentences in the ‘content’ attribute into vectors. Use four vectorization methods (feature extraction methods) (V1) Bag of Words (BoW)  (V2) TF-IDF  (V3) Word2Vec , and (V4) GloVe embeddings
https://machinelearningmastery.com/prepare-text-data-machine-learning-scikit-learn/
https://machinelearningmastery.com/develop-word-embeddings-python-gensim/

Run naive bayes using 80:20 as train-test split. Perform experiments for different combinations of pre-processing approach (P) and vectorization approach (V). For each combination (P1-V1, P1-V2, P1-V3, P1-V4, P2-V1, P2-V2, P2-V3, P2-V4), compute precision and recall values (both expressed as percentage). Use matplotlib to draw bar plots (in single plot) for precision & recall for each configuration. On X-axis, write configurations and on Y-axis is percentage to represent precision and recall.

