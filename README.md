In this project we use Naive Bayes binomial classification to predict who is morely like to have said a new input sentence between subject A and B.

For this purpose we use a small dataset taken from whatsapp conversation between subject A, Krystyna, me, and subject B, Matteo.

The individual messages are stored in 2 different csv files with column “Class” and “Message”.

We use pandas to read the data and MultinomialNB from sklearn to perform naive bayes on our data.

First we use vectorizer.fit_transform to vectorize our messages into the variable “counts” and then we create as “targets”, our classes values.


We use MultinomialNB() to create our classifier and use predict() to predict the new input messages 
