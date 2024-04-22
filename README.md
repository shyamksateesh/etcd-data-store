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

Go to your project directory (the directory where `app.py` is stored) in terminal and type:

```bash
python app.py
```
## Functionalities Implemented

### Key-Value Pair Addition: 

You can add key-value pairs to the etcd database using the "Put Key-Value Pair" functionality. This feature is handled by the `put()` function in `app.py`, located at line 16. Users can input a key and its corresponding value, and upon submission, the key-value pair is stored in the etcd database.

### Retrieving Values by Key: 

Users can retrieve the value associated with a specific key from the etcd database using the "Get Value by Key" functionality. This feature is managed by the `get()` function in `app.py`, found at line 22. Users input a key, and upon submission, the corresponding value is fetched from the etcd database and displayed to the user.

### Deleting Keys: 

The "Delete Key" functionality allows users to remove a key and its associated value from the etcd database. This feature is controlled by the `delete()` function in `app.py`, located at line 29. Users input a key, and upon submission, the key-value pair is deleted from the etcd database if it exists.

### Listing All Keys: 

Users can view a list of all keys stored in the etcd database using the "List All Keys" functionality. This feature is handled by the `list_keys()` function in `app.py`, present at line 39. Upon accessing this functionality, all keys present in the etcd database are fetched and displayed to the user.

### Deleting All Entries: 

The "Delete All Entries" functionality enables users to delete all key-value pairs stored in the etcd database. This feature is managed by the `delete_all()` function in `app.py`, located at line 51. Upon triggering this functionality, all key-value pairs in the etcd database are deleted.
