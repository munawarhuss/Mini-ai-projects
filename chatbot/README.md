# Chatbot Project

This project is a simple AI-powered chatbot built using Python and Hugging Face's open-source language models. It demonstrates how to create a conversational AI application leveraging transformer models.

## Features

- Utilizes Hugging Face’s `transformers` library for NLP tasks
- Implements tokenization, model loading, and inference
- Interactive terminal-based chatbot experience
- Lightweight and easy to extend for further AI experimentation

## Setup Instructions

1. Clone this repository or download the project files.
2. Create and activate a Python virtual environment:
python3 -m venv my_env source my_env/bin/activate

3. Install required dependencies:
pip install -r requirements.txt

4. Run the chatbot:
python chatbot.py


## Notes
requirements.txt content
transformers
torch
Additional notes for Cloud IDE users:
The transformers library provides access to pretrained language models.
torch is the PyTorch backend required by many transformer models.
You can install these inside your virtual environment using the command:
pip install -r requirements.txt