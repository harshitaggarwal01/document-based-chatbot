# document-based-chatbot
A document based chatbot with wikipedia feature

you have to upload documents of your choice and it can answer questions based on the documents, I used nltk for preprocessing the documents. To generate a response I used TFid vectorizer to find similarity between words entered by user and in the documents using cosine similarity. Some basic responses like hey hello bye had to hardcoded. It can also give the first three lines from the Wikipedia page if you type "tell me about _", I used the Wikipedia library for this.

for the dataset we will download from http://www.whatishumanresource.com/human-resource-management (i have provided this as HR.txt)
you can add as many documents as you want.

it is a single file to be run on colab, change the document location accordingly.
