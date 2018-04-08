The vector space model for documents
====================================

The program vsm.py implements a toy search engine to illustrate the
vector space model for documents.

The program asks you to enter a search query, and then returns all
documents matching the query, in decreasing order of cosine
similarity, according to the vector space model.

The document corpus consists of the books of Holy Bible in .txt format.
Every .txt is a book of the Bible.
The books of the same name that contains more than one book in the normal Bible were add in only one file.
Ex: All books of Jonh (Jonh, 1 Jonh, 2 John, 3 John) is only one file .txt.
So, the corpus of the document contais 56 files.
