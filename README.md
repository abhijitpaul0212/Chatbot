# Python-Chatbot

Creating a simple Python chatbot using natural language processing and deep learning for FIS Innovate48 2020

Agenda

    Libraries & Data
    Initializing Chatbot Training
    Building the Deep Learning Model
    Building Chatbot GUI
    Running Chatbot
    Conclusion
    Areas of Improvement
    
Libraries & Data

All of the necessary components to run this project are on the GitHub repository. Feel free to fork the repository and clone it to your local machine. Here’s a quick breakdown of the components:

    train_chatbot.py — the code for reading in the natural language data into a training set and using a Keras sequential neural network to create a model
    chatgui.py — the code for cleaning up the responses based on the predictions from the model and creating a graphical interface for interacting with the chatbot
    classes.pkl — a list of different types of classes of responses
    words.pkl — a list of different words that could be used for pattern recognition
    intents.json — abunch of JavaScript objects that lists different tags that correspond to different types of word patterns
    chatbot_model.h5 — the actual model created by train_chatbot.py and used by chatgui.py
    
    
 REFERENCE:- https://towardsdatascience.com/how-to-create-a-chatbot-with-python-deep-learning-in-less-than-an-hour-56a063bdfc44
