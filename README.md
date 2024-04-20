# Shapes Area Calculator README

This Java program calculates the area of different shapes: circle, rectangle, and triangle. It consists of the following classes and interface:

1. **Circle**: Represents a circle shape with attributes radius and color.

   - `Circle(double radius, String color)`: Constructor method to initialize a Circle object with the provided radius and color.
   
   - Getter and setter methods for radius and color attributes.
   
   - `@Override double getArea()`: Overrides the `getArea()` method from the `Shapes` interface to calculate the area of the circle.

2. **Rectangle**: Represents a rectangle shape with attributes length and width.

   - `Rectangle(double length, double width)`: Constructor method to initialize a Rectangle object with the provided length and width.
   
   - Getter and setter methods for length and width attributes.
   
   - `@Override double getArea()`: Overrides the `getArea()` method from the `Shapes` interface to calculate the area of the rectangle.

3. **Triangle**: Represents a triangle shape with attributes base and height.

   - `Triangle(double base, double height)`: Constructor method to initialize a Triangle object with the provided base and height.
   
   - Getter and setter methods for base and height attributes.
   
   - `@Override double getArea()`: Overrides the `getArea()` method from the `Shapes` interface to calculate the area of the triangle.

4. **Shapes**: An interface defining a method `getArea()` to calculate the area of different shapes.

5. **Main**: Contains the main method to run the program and interact with users.

   - `public static void main(String[] args)`: The main method where the program starts execution. It prompts the user to enter the dimensions of a circle, rectangle, and triangle, creates objects of the corresponding shapes, and calculates their areas.

## Usage

To use the program:

1. Run the `Main` class.
2. Enter the dimensions of the circle, rectangle, and triangle as prompted.
3. The program will calculate and display the area of each shape.

## Requirements

- Java Development Kit (JDK) installed on your system.

