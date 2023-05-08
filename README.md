Download Link: https://assignmentchef.com/product/solved-solution-problem-1-and-2
<br>
PART I:

Create an abstract Java class named “TwoDFigure” in a package named “GEOFIGURES”. This class has 3 attributes:

(1) dimension: a constant, public, of type byte, and set to value of 2

(2) shape: protected, of type String (e.g.: circle, square, etc.)

(3) length unit: protected, of type String (e.g.: cm, m, ft, in)

Class TwoDFigure declaration provides a default constructor, get-methods and set-methods for the variable attributes (shape and length unit), a method to calculate perimeter (calculatePerimeter()) that always returns 0, a method to calculate area (calculateArea()) that always returns 0, and another method (displayFigureData()) that always print out the text “This is a 2D figure.”

IMPORTANT NOTES:

See the sample code of this class in the file twoDFigure.docx

PART II:

Create a Java class named “Circle” in the same package, i.e. GEOFIGURES, that extends the above class TwoDFigure. Class Circle has 2 attributes: radius and PI value. Both of them should be defined as private. Class Circle declaration provides:

a default constructor,

another constructor that accepts radius as a parameter,

get-method and set-method for the attribute radius,

a method to get the diameter,

a method to calculate perimeter (calculatePerimeter()) that overrides the method of the same name of the superclass TwoDFigure and returns the value of perimeter

a method to calculate area (calculateArea()) that overrides the method of the same name of the superclass TwoDFigure and returns the value of area

a method (displayFigureData()) that overrides the method of the same name of the superclass TwoDFigure and prints out information to indicate that the figure is a circle and value of its radius.

IMPORTANT NOTES:

See the sample code of this class in the file circle_new.docx

PART III:

Create a Java class named “Square” in the same package, i.e. GEOFIGURES, that extends the above class TwoDFigure. This class has 1 attribute: side length that should be defined as private. Class Square declaration provides:

a default constructor,

another constructor that accepts its side length as a parameter,

get-method and set-method for the attribute side length,

a method to calculate perimeter (calculatePerimeter()) that overrides the method of the same name of the superclass TwoDFigure and returnsthe value of perimeter

a method to calculate area (calculateArea()) that overrides the method of the same name of the superclass TwoDFigure and returns the value of area

a method (displayFigureData()) that overrides the method of the same name of the superclass TwoDFigure and prints out information to indicate that the figure is a squareand value of its side length.

IMPORTANT NOTES:

See the sample code of this class in the file square_new.docx

PART IV:

Create a Java class named “Rectangle” in the same package, i.e. GEOFIGURES, that extends the above class TwoDFigure. This class has 2 attributes: width and length that both should be defined as private. Class Rectangle declaration provides:

a default constructor,

another constructor that accepts its width and length as two different parameters,

get-methods and set-methods for the attributes width and length,

a method to calculate perimeter (calculatePerimeter()) that overrides the method of the same name of the superclass TwoDFigure and returns the value of perimeter

a method to calculate area (calculateArea()) that overrides the method of the same name of the superclass TwoDFigure and returns the value of area

a method (displayFigureData()) that overrides the method of the same name of the superclass TwoDFigure and prints out information to indicate that the figure is a rectangle and values of its width and length.

PART V:

Write a Java program that can calculate and print out the perimeter and area of a 2D figure. This figure can be either a circle, or a square, or a rectangle. First, the program reads an input of a numeric figure code that identifies which type of 2D figure that the user wants to work with.

The values of figure code are:

1 for circle

2 for square

3 for rectangle

The input of figure code must be verified to be sure that it is valid, i.e. can be only either 1 or 2 or 3.

For the circle, the user enters data of the radius and then its measurement unit (“in” for inch, “ft” for feet, “cm” for centimeter, and “m” for meter) from the console.

For the square, the user enters data of the side length and then its measurement unit (“in” for inch, “ft” for feet, “cm” for centimeter, and “m” for meter) from the console.

For the rectangle, the user enters data of width, data of length, and then the measurement unit (“in” for inch, “ft” for feet, “cm” for centimeter, and “m” for meter) from the console.

The program should check to be sure that each numeric input is not negative and the measurement unit must be one among the listed-above units.

The Java program is another Java class named “FigureCalculator” in the same package, i.e. GEOFIGURES. To provide a solution to the problem, it is expected that inheritance and polymorphism are used in the coding.


