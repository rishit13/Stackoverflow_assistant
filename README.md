# Stackoverflow Assistant
![](./chatbot.webp)

A Natural Language Processing project where programmers can solve their bugs in code or doubts regarding C++ and java by having a natural language conversation with a bot. This was an end-to-end NLU and NLG project which was hosted on telegram and deployed on AWS.

# Prereqisites

OS type and version: macOS Catalina, Version 10.15.7,

System type: 64-bit OS, x64-based processor

Python version: >=3.7


# Overview
The bot utilises a pretrained neural network which was then fine tuned for the question and answers dataset of stackoverflow assistant. A dialogue manager was sed in order to provide the slot taggers and intents from the natural language which were then utilised by the answer ranking system in-order to provide the most appropriate answer. 

The bot was dockeried and deployed on an Aamazon EC2 instance. 

Telegram bot ID : @rish_bot

