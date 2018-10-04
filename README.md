# NLP_track_Lowkey
This track is being designed to learn about Natural Language Processing, focuses on a student perspective without a PhD.

Whenever encountered with a thought or a problem, to associate ourselves with that thought it's important to know about it as much as we can. To do this we need to ask three set of questions WHY, HOW, WHAT.(https://www.youtube.com/watch?v=qp0HIF3SfI4). This will also help the person taking this course to choose the subset in which they want to specialize in.

# Natural Language Processing

Natural Language Processing is the branch of Artificial Intelligence concerned with **Analysis, Generation, Summarization** of Text data.
## Why
http://www.dataversity.net/natural-language-processing/

Let's Start with Topics covered under NLP One by One. I'll try to keep them short and atomic.

# Text Classification
Text Classification is technique for taking text data and assigning a class or label to that data. Text Data can be a document, sentence or word.

 ## Why
This technique is useful for solving problems where we have to automate process of understanding the queries or clustering the document sets. For example, Companies like Ola, Swiggy, Flipkart etc. receive lot of customer complaints & queries everyday. These queries come in large volumes and if satisfactory response is not provided within time, Customers can leave for other services. Response to these queries has to be generated from the concerned department, Like in Ola if you are facing issue with Bill, it should go to the Billing department and if you are facing issue with app itself, it should be sent to Development team. Doing this manually can lead to a bottleneck and choke the whole system. Here, Text Classification comes in and helps us tagging queries with correct labels and sending to concerned team.
Have a look at: https://eng.uber.com/cota/

 ## How
 ### BOW model[Bag of Words]
 While using Text Data we need to represent data in the form which can be processed by Machine Learning algorithms. Bag of Words is one of  the ways to do so.
 Bag of Words is a method to extract features from text documents. These features can be used for training machine learning algorithms. It creates a vocabulary of all the unique words occurring in all the documents in the training set. For example, if you have 3 documents-

D1 - “I am feeling very happy today”
D2 - “I am not well today”
D3 - “I wish I could go to play”

First, it creates a vocabulary using unique words from all the documents -
Unique list of words - ["I", "am", "feeling", "very", "happy", "today", "not","well", "wish", "could","go", "to", "play"]

Then, for each word the frequency of the word in the corresponding document is inserted
![feature representation](https://qph.fs.quoracdn.net/main-qimg-054edc66e34ec439241ea1637350286f.webp)

The above table depicts the training features containing term frequencies of each word in each document. This is called bag-of-words approach since the number of occurrence and not sequence or order of words matters in this approach.

 Definition & Explaination has been taken from [https://www.quora.com/What-is-the-bag-of-words-algorithm]
 ### Count Vectorizer
 
 ### TF-IDF Algorithm

 ## What
