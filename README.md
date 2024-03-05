# Learning AI Chatbot

This chatbot has two purposes:
# 1. Learning NLP
If you are learning machine learning and artificial intelligence and want to implement your own NLP project, this one is a good start. All notebooks are well commented. Follow the code and the comments and then customize the datafile for your own chatbot. 

# 2. ML Course Recommendations
If you are new to the exciting field of machine learning and artificial intelligence and don't know how to get started with, this chatbot will help you. It will give you course recommendations and provide also additional material. 

# Implementation
The implementation is inspired by the following artical: https://chatbotsmagazine.com/contextual-chat-bots-with-tensorflow-4391749d0077

The model is implemented with TensorFlow and uses a simple neural network. 
The gui for running the chatbot is taken from the tutorial by Patrick Loeber: 
https://www.youtube.com/watch?v=RpWeNzfSUHw&list=PLqnslRFeH2UrFW4AUgn-eY37qOAWQpJyg

You can find a simpler PyTorch implementation of a chatbot on his github profile:                           
https://github.com/patrickloeber/pytorch-chatbot?tab=readme-ov-file

# Installation 
Please install TensorFlow, NumPy and the NLTK (Natural Language Toolkit) libraries (e.g. with pip install nltk).

Run once 
```sh
nltk.download('punkt')
```
in the train.ipynb file.
# Usage 
Run train.ipynb notbook first for training the model.

Next run chatbot.ipynb.

You can quite easy customize this chatbot by changing datafile.json. Write your own intents in order to create your own personalized chatbot and rerun the train.ipynb notebook.

Have fun!
