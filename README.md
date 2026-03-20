# Simple Python Chatbot

This is a basic chatbot program written in Python. It responds to a few predefined user inputs and keeps running until the user types `exit`.

## Features

- Responds to simple greetings like `hello` and `hi`
- Answers basic questions like:
  - `how are you`
  - `what is your name`
- Exits when the user types `exit`
- Uses Python dictionary for storing responses
- Uses `random` module for selecting responses

## Requirements

- Python 3.x

## How It Works

The chatbot:
1. Prints a welcome message
2. Takes input from the user
3. Converts the input to lowercase
4. Checks whether the input matches any predefined response
5. Prints the matching response
6. If no match is found, it prints a default response
7. Stops when the user types `exit`
