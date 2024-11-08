# NLP_StopWordandStemmingFromTextInput
A text-processing script that tokenizes input, removes stop words, and applies stemming to simplify word forms.

This script takes user input text, tokenizes it into words, filters out common stop words, and applies stemming to reduce words to their base forms, providing a processed list of words.
Steps:
1. Setup and Downloads: Ensures necessary NLTK data files are downloaded for tokenization and stop word filtering.
2. User Input: Prompts the user to enter text that will be processed.
3. Tokenization: Splits the input text into individual word tokens.
4. Stop Word Removal: Filters out common English stop words, creating a list of meaningful words.
5. Stemming: Initializes the Porter Stemmer and applies it to each filtered word, reducing words to their stems (base forms).
Output: Displays both filtered words (without stop words) and stemmed words, providing a simplified form of each token.
