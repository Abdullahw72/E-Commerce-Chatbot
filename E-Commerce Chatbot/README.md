# E-Commerce Chatbot using NLTK

Following are the details about the processing behind the project:

### Text Pre- Processing with NLTK

<li>Converting the entire text into uppercase or lowercase, so that the algorithm does not treat the same words in different cases as different</li>
<li>Tokenization: Tokenization is just the term used to describe the process of converting the normal text strings into a list of tokens i.e words that we actually want. 
Sentence tokenizer can be used to find the list of sentences and Word tokenizer can be used to find the list of words in strings.</li>

The NLTK data package includes a pre-trained Punkt tokenizer for English.

[+] TF-IDF Approach: 
    TF : TERM FREQUENCY, (How frequent a word appears in a document)
    IDF : INVERSE DOCUMENT FREQUENCY (How rare a word is across documents)
    
    TF = (Number of times term t appears in a document)/(Number of terms in the document)
    IDF = 1+log(N/n), where, N is the number of documents and n is the number of documents a term t has appeared in.
    
[+] Cosine Similarity: 
    Cosine similarity is a measure of similarity between two non-zero vectors. Using this formula we can find out the similarity between any two documents d1 and d2.
    Cosine Similarity (d1, d2) =  Dot product(d1, d2) / ||d1|| * ||d2||
    where d1 and d2 are two non-zero vectors
    
FILES

[+] Intents.json – The data file which has predefined patterns and responses.  
[+] train_chatbot.py – In this Python file, we wrote a script to build the model and train our chatbot.  
[+] Words.pkl – This is a pickle file in which we store the words Python object that contains a list of our vocabulary.  
[+] Classes.pkl – The classes pickle file contains the list of categories.  
[+] Chatbot_model.h5 – This is the trained model that contains information about the model and has weights of the neurons.  
[+] Chatgui.py – This is the Python script in which we implemented GUI for our chatbot. Users can easily interact with the bot.  


STEPS 

[+] Import and load the data file  
[+] Preprocess data  
[+] Create training and testing data  
[+] Build the model  
[+] Predict the response  

Please refer to the uploaded project report for more information.



---
