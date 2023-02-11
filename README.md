# AirBnB_clone
- Building and deploying a clone of the AirBnB website


### First Phase: 
  - A command interpreter to manipulate data without a visual interface, like in a Shell (perfect for development and debugging)
  #### Tasks
  - Building a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances
  - Creating a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
  - Creating all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
  - Creating the first abstracted storage engine of the project: File storage.
  - Creating all unittests to validate all our classes and storage engine
