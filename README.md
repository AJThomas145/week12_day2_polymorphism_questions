# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?  

It means the ability to take different forms.


2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

It means that data types can take many forms.  For example, when we use an Abstract class (Vehicle) as a basis to create other child classes of types of vehicles, inheritance allows for polymorphism as a car class creates cars but it is also a vehicle (hence takes many forms).  We can then use use to make collections of different vehicles (cars, buses, lorries) as an ArrayList of vehicles.  This is only possible with polymorphism.  


3. What can we use to implement polymorphism in Java?

Through the use of inheritance, interfaces and abstract classes. 


4. How many 'forms' can an object take when using polymorphism?

There is no restriction on a number other than what makes sense for the applied code to function as intended.


5. Give an example of when you could use polymorphism.

An abstract class of vehicle can be used to make child classes of different vehicles (car, bus, lorry).  If one person owned multiple vehicles we cant group them as car, bus and lorry as they are different classes.  However all of them are of class vehicle as can be group as such within an ArrayList of vehicles.


# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?

When a class uses other object classes to compose its instance variables. 


7. When would you use composition? Provide a simple example in Java.

When creating a car class in java, it makes more sense to use composition to allow for the creation of the car.  There can be different classes holding key information about parts of the car (engine, tyres etc) that will give far more information relating to them.  These classes can then be used to compose/create the instance variables of the car.


8. Give a difference between composition and aggregation?

composition implies a relationship between classes where the child class cant exist with the parent (an engine needs a car to work).  Aggregation implies a relationship where the child can exist independently of the parent class (a car and its pasengers)


9. What is/are the advantage(s) of using composition/aggregation?

They allow for associations between classes and allows for the re-usability of code.  This will produce better structured code that can be exapnded more easily.  


10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?

They are also destroyed as they cant exist without the parent class.


11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?

They will not be destroyed.  In aggregation the class has a relationship with the other class but can exist independently.
