# AirBnB_clone
- Building and deploying a clone of the [AirBnB](https://www.airbnb.com/).


### First Phase: 
  - The console is a command interpreter to manage objects abstraction between objects and how they are stored.
    To see the fundamental background of the project visit the [Wiki](https://github.com/ralexrivero/AirBnB_clone/wiki).
  - A command interpreter to manipulate data without a visual interface, like in a Shell (perfect for development and debugging)
  
  #### Tasks
  - Building a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances
  - Creating a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
  - Creating all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
  - Creating the first abstracted storage engine of the project: File storage.
  - Creating all unittests to validate all our classes and storage engine
  - All the classes are handled by the `Storage` engine in the `FileStorage` Class.
