# Style Transfer



## Requirements

- Python 3.11.5
- Pyenv

`tensorflow-datasets` requires CMake. When working on a MacBook Pro M2 the best way to install CMake is via Homebrew: `brew install cmake`


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