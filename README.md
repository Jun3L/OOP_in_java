# OOP_in_java

**OOP Learning Roadmap with Tasks (Beginner → Advanced)**

**Stage 1: Basics of Classes and Objects**

Goal: Understand classes and objects.

Tasks:
Create a Student class with name and age, then create an object and print the details.
Create a Car class with color and speed, then change values using objects.
Create a Book class with title, author, price, and display them.

**Stage 2: Constructors**

Goal: Learn how to initialize objects with constructors.

Tasks:
Add a default constructor to Student and create objects.
Add a parameterized constructor to Car and initialize objects with color and speed.
Create multiple Book objects using parameterized constructor and print their info.

**Stage 3: Encapsulation (Getters & Setters)**

Goal: Protect object data.

Tasks:
Make age private in Student and create getter and setter.
Make balance private in BankAccount class and implement deposit/withdraw methods.
Restrict marks in Student class to be 0–100 using setters.

**Stage 4: Inheritance**

Goal: Reuse code and create hierarchies.

Tasks:
Create Vehicle class → extend Car and Bike with different speeds/colors.
Create Employee → extend Manager and Developer with extra attributes.
Override a method in subclass to display details differently.

**Stage 5: Polymorphism**

Goal: Learn method overloading and overriding.

Tasks:
Overload a method calculateArea() for square, rectangle, circle.
Override a method display() in Employee subclasses (Manager, Developer).
Create an array of Employee objects and call the display() method to see polymorphic behavior.

**Stage 6: Abstraction**

Goal: Hide unnecessary details.

Tasks:
Create an abstract class Shape with abstract method draw() → implement in Circle and Rectangle.
Create an interface Drawable → implement in Square and Triangle.
Build a mini program where all shapes can draw themselves using abstraction.

**Stage 7: Advanced OOP Concepts**

Goal: Master static, final, inner classes, and this/super.

Tasks:
Create a MathUtil class with static methods (add, subtract, multiply).
Use final keyword to prevent overriding in a class/method.
Create an inner class in Car called Engine and access it.
Use this keyword to distinguish object variables from parameters.
Use super keyword to call parent class constructor.

**Stage 8: Exception Handling in OOP**

Goal: Make objects safer.

Tasks:
Handle ArithmeticException in a Calculator class.
Handle ArrayIndexOutOfBoundsException while accessing a student array.
Create a custom exception InvalidMarkException for invalid student marks.

**Stage 9: Collections with OOP**

Goal: Store and manage multiple objects.

Tasks:
Create an ArrayList of Student objects and display all students.
Create a HashMap of Employee ID → Employee object.
Filter students with marks > 75 from ArrayList and display them.

**Stage 10: Mini OOP Projects**

Goal: Integrate all OOP concepts.

Projects:
Student Management System
Classes: Student, Course
Features: Add, display, search students
Use ArrayList, encapsulation, inheritance for GraduateStudent
Banking System
Classes: BankAccount, Savings, Current
Features: Deposit, Withdraw, Check balance
Exception handling for invalid operations
Simple Game Simulation
Classes: Player, Enemy, Weapon
Features: Display stats, attack, defend
Use polymorphism for different enemy types
