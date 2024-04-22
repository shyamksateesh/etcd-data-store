# Etcd Key-Value Store Project

This project implements a key-value store using etcd as the backend storage and a Flask application to interact with it.

## Requirements

- [etcd](https://etcd.io/)
- [Python](https://www.python.org/)
- [pip](https://pypi.org/project/pip/)
- [Flask](https://flask.palletsprojects.com/en/2.1.x/)

## Installation

### Install etcd

You can install etcd on macOS using Homebrew:

```bash
brew install etcd
```
### Install python-etcd3 package

```python
pip install etcd3
```

## Running the Project

### Starting etcd Server

You can go to your terminal and type this:

```bash
etcd
```

### Running Flask App

Go to your project directory (the directory where app.py is stored) in terminal and type:

```bash
python app.py
```

