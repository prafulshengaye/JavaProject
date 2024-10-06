# JavaProject

md
# Java Basics: Autoboxing/Unboxing and Shape Calculations

This project demonstrates two Java concepts:
1. **Autoboxing and Unboxing**: How Java automatically converts between primitive types and their corresponding wrapper classes.
2. **Shape Interface and Implementation**: Calculating area and perimeter for different shapes (Circle and Rectangle) using an interface.

## Question 1: Autoboxing and Unboxing
The program demonstrates:
- Autoboxing: Automatically converting primitive types (like `int` and `double`) into their corresponding wrapper classes (`Integer` and `Double`).
- Unboxing: Converting wrapper class objects back to primitive types.

### Sample Output:

Primitive int: 10
Autoboxed Integer: 10
Autoboxed Integer: 20
Unboxed int: 20
Primitive double: 15.5
Autoboxed Double: 15.5
Autoboxed Double: 25.75
Unboxed double: 25.75


## Question 2: Shape Interface and Implementation
This part includes:
- A `Shape` interface with methods `area()` and `perimeter()`.
- Two classes `Circle` and `Rectangle` that implement the `Shape` interface and provide specific calculations for each shape.

### Sample Output:

Circle:
Radius: 5.0
Area: 78.53981633974483
Perimeter: 31.41592653589793

Rectangle:
Width: 4.0, Height: 6.0
Area: 24.0
Perimeter: 20.0


## How to Run the Code
1. Clone the repository to your local machine.
2. Ensure you have Java installed. You can verify with:
   bash
   java -version
   
3. Compile and run each file using the following commands:
   - For **Question 1** (Autoboxing and Unboxing):
     bash
     javac AutoboxingUnboxing.java
     java AutoboxingUnboxing
     
   - For **Question 2** (Shape Calculations):
     bash
     javac ShapeTest.java
     java ShapeTest
     

## Project Structure:

.
├── AutoboxingUnboxing.java    # Question 1 Code
├── ShapeTest.java             # Question 2 Code
└── README.md                  # This file


## Author
Praful Shengaye


### How to Use:
1. Save this content in a file named README.md.
2. Add it to your project folder.
3. Push your project to GitHub, and it will automatically show this file as the main description for your project.

Good luck with your GitHub project!
