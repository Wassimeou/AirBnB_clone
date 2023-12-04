#0x00. AirBnB clone - The console

##description of the project

###this is the AirBnB project
### The goal of the project is to deploy on our server a simple copy of the AirBnB website.
### for this project we have this files and Directories:
### models directory will contain all classes used for the entire project. 
### A class, called “model” in a OOP project is the representation of an object/instance.
### tests directory will contain all unit tests.
### console.py file is the entry point of our command interpreter.
### models/base_model.py file is the base class of all our models. It contains common elements:
>>> attributes: id, created_at and updated_at
>>> methods: save() and to_json()
>>> models/engine directory will contain all storage classes (using the same prototype). 
### For the moment we will have only one: file_storage.py.

## description of the command interpreter
### provides a command-line interface where users input text commands
### The interpreter uses a loop to read all lines from its input,
### parse them, and then dispatch the command to an appropriate command handler.

## exemples:
### [cat]> View File Contents
### [ls]> list Files
### [cd]> Change directory