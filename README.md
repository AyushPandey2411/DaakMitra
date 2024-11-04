# DaakMitra Chatbot

DaakMitra is an interactive, NLP-powered chatbot that provides responses based on user input using a trained neural network model. This project utilizes the Keras library for deep learning and a Flask API for potential integration with web applications.

## Features

* **Real-Time Text Responses:** The chatbot processes user messages and provides accurate responses based on the predicted intent.
* **Intent Recognition:** Using a pre-trained deep learning model, DaakMitra identifies the user's intent to generate relevant replies.
* **Natural Language Processing:** Text is processed with tokenization and lemmatization, allowing for better understanding and response accuracy.
* **Console and Web Compatibility:** Initially runs in a console environment, with potential for deployment in web applications using Flask.

## Technical Specifications

* **Model Architecture:** The chatbot is powered by a Keras-based deep learning model (`chatbot_model.h5`) trained to classify various intents.
* **Tokenization & Lemmatization:** Uses NLTK to preprocess and standardize user input, enhancing the accuracy of intent prediction.
* **Error Handling:** Only intents with a probability above a specified threshold are considered, improving response quality.
* **Flask API Integration:** For future web integration, the chatbot API is set up with Flask and CORS to allow frontend applications to interact seamlessly.

