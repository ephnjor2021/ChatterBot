# ChatterBot

ChatterBot is an interactive chatbot designed to streamline communication and enhance user experiences across various platforms.

## Project Overview

The project uses ChatterBot Library that combines language corpora, text processing, machine learning algorithms, and data storage and retrieval to allow you to build flexible chatbots.
You can build an industry-specific chatbot by training it with relevant data. Additionally, the chatbot will remember user responses and continue building its internal graph structure to improve the responses that it can give.

## Prerequisites

Before you get started, make sure that you have the following:
- Python Version 3.7.9 installed.
- A Linux Based Operating System.
- Knowledge of Python concepts.

## How to Install the Project Dependencies

Create and activate a [virtual environment](https://docs.python.org/3/library/venv.html), then install the necessary dependencies:

```bash
$ python -m venv venv
$ source venv/bin/activate
(venv) $ python -m pip install -r requirements.txt
```

## Running the Project

To run the project, navigate into the project root folder and start the interactive command-line interface to train and test the chatbot by running `bot.py`:

```bash
(venv) $ python bot.py
```

After training, you'll see an interactive prompt that you can chat with:

```text
You: hi
Bot: Welcome, friend
You: thanks for the green welcome
Bot: I let you
You: you let me be here?
Bot: It's a monsters!
You: did you mean monstera?
Bot: The leafs that she had are getting dryer and dryer. But she’s also growing plenty of new ones
You: who?
Bot: Do raindrops touch their leaves?
You: very philosophical!
Bot: Lol
You: ;)
Bot: I don't grow any crop at home
You: no crops in pots
Bot: Ah, gotcha!
```

The bot will learn from the replies you give and improve its accuracy. You can quit the interactive prompt by typing any of the `exit_conditions` defined in `bot.py`.

## Conclusion

ChatterBot is a promising project that can offer practical solutions to the modern customer support relationships. 
I am enthusiastic about developing a tool that can enhance customer relationships through meaningful replies on customized issues and products. Let's embark on this journey together!

You can check out a brief video demo of the ChatterBox [here](https://youtu.be/GmKy0RoSl18).

## Author

- [Ephraim Gathoni](https://www.linkedin.com/in/ephraim-njoroge/).
