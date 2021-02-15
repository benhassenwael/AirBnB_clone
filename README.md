# AirBnB Clone
Welcome to the AirBnB clone project! (The Holberton B&B) <br />
The HBNB project clone th [AirBnB website](https://www.airbnb.com/) to buil a first full web application using : *HTML/CSS, Database storage, API, Front-end integration ...* <br />
* First will put in place a parent class called [*BaseModel*](https://github.com/JennyHadir/AirBnB_clone/blob/master/models/base_model.py) to take care of the initialization, serialization and deserialization of other instances <br />
* Second will create all classes used for AirBnb: <br />
* [User](https://github.com/JennyHadir/AirBnB_clone/blob/master/models/user.py)
* [State](https://github.com/JennyHadir/AirBnB_clone/blob/master/models/state.py)
* [City](https://github.com/JennyHadir/AirBnB_clone/blob/master/models/city.py)
* [Place](https://github.com/JennyHadir/AirBnB_clone/blob/master/models/place.py)
<br />

* Then comes the first abstracted storage engine of the project : [File storage](https://github.com/JennyHadir/AirBnB_clone/blob/master/models/engine/file_storage.py)
* Last but not least  there's [unittests]() to valide all our classes and storage engine
* Finally we have a [command interepter](https://github.com/JennyHadir/AirBnB_clone/blob/master/console.py)
## What’s a command interpreter? 
It's a command that helps to manage the objects of our project using [the cmd module](https://docs.python.org/3.4/library/cmd.html)
* Create a new object (ex: a new User or a new Place)
* Retrieve an object from a file, a database etc…
* Do operations on objects (count, compute stats, etc…)
* Update attributes of an object
* Destroy an object

## Usage
$ ./console.py

## Examples
### In interactive mode:

$ ./console.py <br />
(hbnb) help <br />

Documented commands (type help <topic>): <br />
========================================
EOF  help  quit <br />

(hbnb) <br />
(hbnb) <br />
(hbnb) quit <br />
$ <br />
## In non-interactive mode: (like the Shell project in C)

$ echo "help" | ./console.py <br />
(hbnb) <br />

Documented commands (type help <topic>): <br />
========================================
EOF  help  quit <br />
(hbnb) <br />
$ <br />
$ cat test_help <br />
help <br />
$ <br />
$ cat test_help | ./console.py <br />
(hbnb) <br />

Documented commands (type help <topic>): <br />
========================================
EOF  help  quit <br />
(hbnb) <br />
$ <br />

## Authors
[Hadir Jenni](https://github.com/JennyHadir) <br />
[Wael Ben Hassan](https://github.com/benhassenwael)
