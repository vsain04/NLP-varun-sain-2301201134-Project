# NLP-varun-sain-2301201134-Project

Project 1: University FAQ Chatbot

Goal:
Create a chatbot that answers student queries about university information such as admissions, fees, timetable, hostel, exams, etc.

Concepts Used:

1. Text preprocessing (tokenization, stopword removal, lemmatization)

2. TF-IDF or Word Embeddings for query matching

3. Cosine similarity for retrieving the best answer

Tools:
Python (NLTK, Scikit-learn, or spaCy)

Dataset:
Self-created CSV with Question and Answer pairs (example:

1. Question: "How much is the admission fee?"

2. Answer: "Admission fee is 5000.")

Workflow Solution:

1. Preprocess FAQ dataset: Tokenize, remove stopwords, lemmatize all questions and answers.

2. Preprocess user input query: Same steps as above.

3. Similarity Calculation: Compute cosine similarity between the user query and FAQ dataset (using TF-IDF or embeddings).

4. Retrieve Answer: Return the best matching answer from the dataset.




Project 2: Customer Support Chatbot for Online Shopping

Goal:
Build a chatbot to handle basic customer queries (order tracking, return policies, delivery, product FAQs).

Concepts Used:

1. Intent recognition (classify query type)

2. Named Entity Recognition (extracting order numbers, product names)

3. Rule-based and similarity-matching responses

Tools:
Python (NLTK, spaCy, Rasa for advanced bots)

Dataset:
Sample customer queries mapped to responses (example:

1. "Where is my order 12345?" → "Your order 12345 is out for delivery."

2. "How can I return a product?" → "You can return products within 15 days via our online portal.")

Workflow Solution:

1. Preprocess user query: Tokenize, remove stopwords, lemmatize.

2. Intent Classification: Order status, return policy, product info, etc.

3. Entity Extraction: For order numbers, product names using NER.

4. Response Generation: Provide the right predefined response from dataset.
