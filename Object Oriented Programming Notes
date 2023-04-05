Object Oriented Programming (aka OOP)
  - "focuses on how to manipulate the data of the object rather than the logic required to manipulate them"
  - used to design modular reusable software systems
  - designs programs with creation of Objects
  - focuses on the definition of data 
        - prioritizes inputs data -> processing data-> outputs calculated result (which is a main component of procedure-oriented programming)
  - The goal is to create an object that we can define and provide functionality to solve problems

Objects:
  - IS AN INSTANCE
  - States: The characteristic, Measurable data of an object
  - Behaviour: The available functionality of the object (what can it do?)
  - attributes refer to objects data
  - methods refer to its code
  
in Com Sci:
  - can be a variable, a data structure, a function, or a method; therefore, a location in memory having a value that can be referenced by an identifier

vs 

in OOP:
  - instance of a class where this object can be either a variable, a function, a data structure or a combination
  
  Ex. Dog 
  - attributes: name, colour, breed, ishungry
  - method: bark(), eat(), sleep()
  
 Class:
  - an abstract description of all objects that can be made from this set class where an object can be instantiated from
  - contains attributes (acessible tools)
  1. Fiedlds: belong to an object or a class (either belongs to object in class or class itself)
  2. Methods: belong to the object or the object can call can be created like regular function suing "def"
  
  formatting:
1. define the name of the class with "class"
2. indent to define its attributes
3. assign a variable with an instantiation of the class to interact with it
*use parentheses when calling the class name.

      ex. # Person Class
    class Person:
      pass # An Empty Block
    #end of Person Class

    student1 = Person() #student1 is now a Person Object
    print(student1)
 -----------------------------   
    
    ex. # Person Class w methods   
    class Person:
      def greet(self):
        print(‘Hello, how are you?’)
    #end of greet
    #end of class Person
    p = Person()
    p.greet() # outputs
----------------------------

Initialization method:
- def __init__(self):
- self parameter is used to denote that the method is applied and accessible for the object itself
- self will also treat its own attributes as local
*double underscored to create key hidden features that allow  overwriting

Encapsulation:
- Information Hiding
- Restricts the access to the classes or objects attributes or methods
- allows data proetction 
- prevents some methods from being returned or called
- in python, hide attributes and methods by using a double underscore __ 

ex. class Student:
  def __init__(self,nameF, nameL, num):
    self.firstName = nameF
    self.lastName = nameL
    self.__studentNumber = num
  
  def __getStudentNumber(self):
    return self.__studentNumber
    
 -------------------------------------
 
Overloading: Two methods in one class that have the same method name, but different parameters
  - NO OVERLOADING IN PYTHON
  - type of polymorism
  
Overriding: Two methods with the same method name and parameters
  - allows the child class to implementate method that exists in the parent class
  
 Polymorphism: A method that can be used across different classes and object that is dependent on the parameters
  - many forms
  - where set of inherited classes have the same methods
  
  ex. 
  class Bear:
    def sound(self):
        print("Groarrr")
 
  class Dog:
      def sound(self):
          print("Woof woof!")
 -----------------------------------
  Base overrides:
    - Two different classes have a same attributes and methods
    - A child of a parent have an overrided method where the child would utilize the method differently
    
__repr__ → Allows us to present a printable version of our object
__str__ → Allows us to convert our object to a string

Inheritence:
  - When an object or class is based on another class; where its features are from a parent class
  - can branch off like tree or be a hybrid of different types
  - usually not required to use 
      - one wrong class can make all wrong 
      - therefore hard to fix
      - old opertaing systems used to use and many companies are still using decades old code
  
      -Single Inheritance: inherits the features of a single  parent class
      -Multiple Inheritance: inherits the features of a multiple diff arent classes
      -Multilevel Inheritance: inherits from another subclass
      
   - If a child class inherits the parent class:
          -The child does not need a new __init__() method UNLESS it requires new attributes
          -The child does not need to reinstate the parent’s methods UNLESS you override them
          
   -types of multiple-inheritenc:
            1. Multi-Generational
                Grandparent → Parent → Child
            2. Multi-Parent (Not limited to two)
                  Parent A \
                        > Child
                  Parent B /

            3. Mixture of  both

          
   

          
     




  

    
 





  

 
 

  
  
  

  
 
