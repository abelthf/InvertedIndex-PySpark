# InvertedIndex-PySpark

a. You are given a file called docs.zip. Inside the docs directory there are seven text files: d1.txt to d7.txt. You should lower case each word and use the documents to generate an inverted index. Do not remove any stop words.
b. Create an inverted index which stores postings with frequency. Use filenames with .txt removed as document ids. You do not need to store position information in these postings.
c. The output format should be as follows: Every line should correspond to one word, such that lines are sorted in lexicographical order of words with the following format.
Word#docID:freq;docID:freq;docID:freq,… e.g., weapons#d4:2;d5:1;d6:3;d7:3
