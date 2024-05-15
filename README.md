# Woxsen-Enquiry-Chatbot-System
Welcome to the Woxsen Enquiry Chatbot System This chatbot is designed to assist users with queries about our university. It uses natural language processing (NLP) techniques to understand user inputs and respond accordingly.
# Features
- Natural Language Understanding: Utilizes NLP libraries like NLTK for tokenization and lemmatization.
- Machine Learning Model: Employs a pre-trained TensorFlow model to classify user intents.
- Dynamic Responses: Generates responses based on the predicted intent using a JSON database of predefined answers.

# Getting Started
**Prerequisites**
Ensure you have these following packages installed:
- numpy
- tensorflow
- nltk
- random
- json
- pickle

# Techniques Used
1. **Lemmatization** :
Lemmatization helps in standardizing words so that variations of the same word can be treated as the same token. This is important in tasks like text analysis, where you want to focus on the underlying meaning of words rather than their surface variations.
2. **Bag of Words (BoW)** :
Bag of Words is a method used for representing text data in NLP. It involves creating a vocabulary of unique words present in the corpus (collection of text documents) and then representing each document as a vector, where each dimension corresponds to a word in the vocabulary, and the value represents the frequency of that word in the document.

In NLP tasks, lemmatization is often performed as a preprocessing step to normalize the text, while bag of words is a common technique used for feature extraction and representation of text data. Lemmatization helps reduce the vocabulary size by collapsing different inflected forms of a word into a single lemma, which can improve the effectiveness of bag of words representation.

# Acknowledgments
- Special thanks to the TensorFlow and NLTK communities for their support and resources.
- Appreciation to the Woxsen community for their continuous feedback and encouragement.
