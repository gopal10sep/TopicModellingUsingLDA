# TopicModellingUsingLDA
LDA assumes documents are produced from a mixture of topics. Those topics then generate words based on their probability distribution. Given a dataset of documents, LDA backtracks and tries to figure out what topics would create those documents in the first place. By using the topic modelling technique, we can get an insight so as to what a given document is all about and can tell about the theme of the document.

Implementation of the algorithm:
The user shall enter the path of the PDF file and he can deduce the topic by studying the probability
distribution of the terms in the topic. He will get the probability distribution of the top four words
of the topic which can further be changed by changing the value of the variable num_words.


Packages Needed (Commands for a Linux System):
1. sudo apt-get install python-tk
2. sudo apt-get install python-matplotlib
3. sudo pip install --user numpy scipy matplotlib ipython jupyter pandas sympy nose
4. sudo apt-get install python-dev libxml2-dev libxslt1-dev antiword unrtf poppler-utils pstotext
tesseract-ocr flac ffmpeg lame libmad0 libsox-fmt-mp3 sox libjpeg-dev
5. sudo pip install textract
6. sudo pip install --upgrade gensim
//Python provides many great libraries for text mining practices, “gensim” is one such clean and
beautiful library to handle text data. It is scalable, robust and efficient.
7. Open a Python console and do the following:
>>> import nltk
>>> nltk.download()


Working:
We can then deduce that the given pdf tells us about ‘Switching techniques’ or ‘Packet switching’.
Input: PDF FILE PATH
OUTPUT: Top 4 related words for that topic.
