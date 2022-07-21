# Language-Modelling
* Took the dataset **RealDonaldtrump.csv https://www.kaggle.com/code/nulldata/basic-nlp-with-trump-tweets/data** and perform following operations on it </br>
1) Split your data into 80% training and 20% test sets. </br>

2) Removed punctuation marks. But as the full stop is the sentence marker, keeping it in the text in case We need to tokenize sentences. </br>

3) Remove the newline characters. </br>

4) Remove stopwords. </br>

5) Use the n-grams module from nltk.util package to build bigrams and trigrams. </br>

6) Find the frequencies of bigrams and trigrams in the corpus. Tabulate them and show the histogram. Compare it with Zipf's Law. </br>

7) Do Add-1 smoothing (Laplace) </br>

8) Build a dictionary showing bigram and trigram probabilities against each sorted in increasing order </br>

9) Retabulate the reconstituted counts for the bigrams and the trigrams </br>

10) Redo the histogram and compare it again with Zipf's Law </br>

11) Take a four-word string as the test sample and find both its unigram, bigram, and trigram perplexities </br>

12) Natural Langauge Generation Task: Based on step 7, build CDF (Cumulative Distribution Function). Generate a random number and compare it with the CDF. Pick the word whose CDF value is closest to it and return it as the generated text </br>

13) Build the Shannon game as discussed in the class. Predict the last word (hide it during prediction time) of the tweets in the test set based on one word before (Bigram modeling), and two words before (trigram modeling), and evaluate the results using accuracy </br>
