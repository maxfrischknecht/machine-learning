# Anime Quote Generator

A fine-tuned distilgpt2 model for generating manga-style quotes, trained on a curated dataset of anime and manga quotes.

> Life is not the end of all things but a journey. The beginning will be as long and beautiful as you can find it. You are free to live your way through life’s path. Your destiny is what makes up for it all. True, but when.

[See the Notebook here.](./generative-quotes-transfer_v1.ipynb)

## 🚀 Features

- Fine-tuned distilgpt2 for short, meaningful quotes.
- Generates diverse and creative responses.
- Supports custom input prompts.


## Requirements

- Python 3.11.5
- Pyenv


## Setup

Set local Python version

```sh
pyenv local 3.11.5
```

Create and activate a virtual env

```sh
python -m venv .venv
```

```sh
source .venv/bin/activate
```

Install dependencies

```sh
pip install --upgrade pip
pip install -r requirements.txt
```

To exit the virtual environment
```sh
deactivate
```

Update the requierments.txt

```sh
pip freeze > requirements.txt
```