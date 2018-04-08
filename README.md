The vector space model for documents
====================================

The program vsm.py implements a toy search engine to illustrate the
vector space model for documents.

The program asks you to enter a search query, and then returns all
documents matching the query, in decreasing order of cosine
similarity, according to the vector space model.

The corpus of the document consists in the books of the Holy Bible in .txt format.
All .txt is a book from the Bible.
Books of the same name that contain more than one book in the normal bible have been added in just one file.
Ex: All of John's books (John, 1 John, 2 John, 3 John) are just a .txt file.
Thus, the document's corpus contains 56 files.
