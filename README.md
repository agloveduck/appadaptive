# app adaptive
# "category_similarity.csv" file
This file contains a similarity matrix that indicates how similar each category is to every other category.
I use a script to calculate category_similarity. It utilizes pre-trained GloVe word vectors to represent categories as vectors and measures their similarity using cosine similarity. 
The script reads category data from a CSV file, processes the category text, and generates a similarity matrix to indicate how similar each category is to one another.
The "glove.6B.300d.txt" file, which contains pre-trained word vectors, is not included due to its large size. So I just use the result of the script as this project's input.