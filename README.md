# LAB-WEEK-5---TRIANGLEWeek 05 - Lab 05 Triangle Scenario. First Draw UML. Java developers follow java rules and python developers will follow python rules.
Write a class Triangle with three instance double variables, namely sideA, sideB, and sideC. The class must have the following methods: 
A default constructor that creates a triangle with all sides being equal to 1.0.
A one-parameter constructor that accepts a double and creates an equilateral triangle with all sides equal to the passed parameter.
-A two-parameter constructor that accepts two doubles x and y, and creates an isosceles triangle with sides x, x, and y. 
-A three-parameter constructor that accepts three doubles x, y, and z, and creates a triangle with sides respectively equal to x, y, and z. 
-A constructor that accepts a reference to an existing triangle and creates a corresponding clone; it should also return a reference to the cloned triangle.

n the Java version, implement getters and setters using standard naming conventions. 

Include a class method objectCount() which returns the current count of how many objects of type Triangle have been created. Include an instance method perimeter() which calculates and returns the perimeter of the triangle. Include another instance method isRightAngled() which returns true if the triangle is right-angled, and false otherwise. Finally, include an instance method toString() which returns a suitable string representation of the current object. 
Week 05 - Lab 05 Triangle Scenario. (Pythonic version Instruction) 
In the Python version, make use of single constructor that do all the jobs demanded by multiple constructors and @property decorator for exposing and validating side values. This problem is designed to give you hands-on practice in object-oriented concepts such as constructor overloading, object cloning, static members, encapsulation, and basic geometric logic.
