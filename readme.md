# Basic Flask webapp

This was based on the following tutorial from freecodecamp.org:

https://www.youtube.com/watch?v=Z1RJmh_OqeA

## Installation

To install, first create and activate a virtual environment .
```
$ python -m venv /path/to/new/virtual/environment
$ source /path/to/new/virtual/environment/bin/activate
```

Then, we install the dependencies using `pip`

```
$ pip install -r requirements.txt
```

## Running

To run the service, execute

```
$ gunicorn -w 4 -b 0.0.0.0 'app:app'
```
