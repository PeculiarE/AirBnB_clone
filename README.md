# 0x00.AirBnB Clone - The Console

## Project Description

This project is the first step towards building a full web application: an AirBnB clone.
This first step consists of a custom command-line interface for data management and the base classes for the storage of this data. This console/command-line interpreter can be used to store objects in and retrieve objects from a JSON.

## Starting the Console
To start, navigate to the project folder and enter `./console.py` in the shell.

## Using the Console
The console can:
- Create a new object (ex: a new User or a new Place)
- Retrieve an object from a file, a database etc...
- Do operations on objects (count, compute stats, etc...)
- Update attributes of an object
- Destroy an object

To access these functionalities, run the following commands:
- `create` - to create an object
- `show` - to show an object (based on id)
- `destroy` - to destroy an object
- `all` - to show all objects, of one type or all types
- `quit` or `EOF` - to quit the console
- `help` - to see descriptions of commands

### Examples:

**Create**

`create <class name>`

Example: `create BaseModel`

**Show**

`show <class name> <object id>`

Example: `show User my_id`

**Destroy**

`destroy <class name> <object id>`

Example: `destroy Place my_place_id`

**All**

`all` or `all <class name>`

Example: `all State`

**Help**

`help` or `help <command>`

Example: `help` or `help quit`

## Environment

This project is interpreted/tested on Ubuntu 14.04 LTS using python3 (version 3.4.3)
