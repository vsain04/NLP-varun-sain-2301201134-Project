# NLP-varun-sain-2301201134-Project

Project 1: University FAQ Chatbot

Goal:
Create a chatbot that answers student queries about university information such as admissions, fees, timetable, hostel, exams, etc.

Concepts Used:

Text preprocessing (tokenization, stopword removal, lemmatization)

TF-IDF or Word Embeddings for query matching

Cosine similarity for retrieving the best answer

Tools:
Python (NLTK, Scikit-learn, or spaCy)

Dataset:
Self-created CSV with Question and Answer pairs (example:

Question: "How much is the admission fee?"

Answer: "Admission fee is 5000.")

Workflow Solution:

Preprocess FAQ dataset: Tokenize, remove stopwords, lemmatize all questions and answers.

Preprocess user input query: Same steps as above.

Similarity Calculation: Compute cosine similarity between the user query and FAQ dataset (using TF-IDF or embeddings).

Retrieve Answer: Return the best matching answer from the dataset.




Project 2: Customer Support Chatbot for Online Shopping

Goal:
Build a chatbot to handle basic customer queries (order tracking, return policies, delivery, product FAQs).

Concepts Used:

Intent recognition (classify query type)

Named Entity Recognition (extracting order numbers, product names)

Rule-based and similarity-matching responses

Tools:
Python (NLTK, spaCy, Rasa for advanced bots)

Dataset:
Sample customer queries mapped to responses (example:

"Where is my order 12345?" → "Your order 12345 is out for delivery."

"How can I return a product?" → "You can return products within 15 days via our online portal.")

Workflow Solution:

Preprocess user query: Tokenize, remove stopwords, lemmatize.

Intent Classification: Order status, return policy, product info, etc.

Entity Extraction: For order numbers, product names using NER.

Response Generation: Provide the right predefined response from dataset.
