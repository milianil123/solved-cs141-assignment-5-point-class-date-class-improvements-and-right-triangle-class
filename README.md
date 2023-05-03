Download Link: https://assignmentchef.com/product/solved-cs141-assignment-5-point-class-date-class-improvements-and-right-triangle-class
<br>
Point Class

Write a definition of a class named Point that might be used to store and manipulate the location of a point on the plane. The point is stored as two coordinates: x and y. You will need to declare and implement the following methods:

<ol>

 <li>Two constructors:

  <ol>

   <li>no-argument constructor that sets the point coordinates to (0,0), and</li>

   <li>a constructor that takes x and y coordinate of the point and sets member variables.</li>

  </ol></li>

 <li>Method set that sets the private data after an object of this class is created.</li>

 <li>A method to move the point by an amount along the vertical and horizontal directions specified by the first and second arguments: move(double dx, double dy)</li>

 <li>The method to rotate the point by 90 degrees clockwise around the origin.</li>

</ol>

<strong>Hint:</strong> when point is getting rotated 90 clockwise around the origin the following        changes happen to its coordinates:

<strong> </strong>xrotated = y;     yrotated = -x .

<ol start="5">

 <li>two accessor methods to retrieve the coordinates of the point Call your file java.</li>

</ol>




PointDemo.java file contains test cases for the Point class. It is provided with the assignment. make sure it works correctly with the class you wrote.

<h1>Date Class Improvements</h1>







Start your work with the class Date provided in <strong>Date.java</strong> file.

Make the following improvements to the class:

<ol>

 <li>Replace all error-handling code that ends with System.exit(0) with a statement that throws Illegal Argument Exception. Please see detailed description in the commented sections in the code. 2. Add 3 methods (with different names) to print the date in 3 different formats:</li>

</ol>

<h2></h2>

Call the source code files Date.java.




Write a class with main() that uses your class.

<ul>

 <li>Please do not collect input from the user. Instead call ALL the methods of the class with the data you choose to make sure the methods work properly. In the comments explain why you decided to use these particular test cases.</li>

 <li>Have try/catch blocks that handle Illegal Argument Exception. Make sure you write code that invokes methods throwing Illegal Argument Exception in main(). Please leave it in your code for me to see. You can comment it out if it interrupts the flow of your program.</li>

</ul>

<strong> </strong>

Call the source code files DateDemo.java.

<strong> </strong>

<h1>Right Triangle Class</h1>




Write a RightTriangle class that has the following fields:

<ul>

 <li>legA: a double</li>

</ul>

<h2><sup>•</sup> legB: a double</h2>




The class should have the following methods:




<ul>

 <li><strong>No-argument constructor</strong>. Sets fields to 0</li>

 <li><strong>Constructor</strong>. Accepts legs of the right triangle as arguments. Constructor throws Illegal Argument Exception when one or both legs are set to 0 or negative number(s)</li>

 <li><strong>setLegA(), setLegB()</strong> – mutator methods. Both methods throw Illegal Argument Exception when leg is set to 0 or negative number.</li>

 <li><strong>getLegA(),getLegB()</strong>-accessor methods.</li>

 <li><strong>getHypotenuse() </strong>– calculates and returns hypotenuse of the triangle.</li>

 <li><strong>GetArea</strong>() – calculates and returns area of the right triangle</li>

 <li><strong>getPerimeter()</strong>– calculates and returns perimeter of the triangle Call the source code files java.</li>

</ul>




Write a class with main() that uses your class.




<ul>

 <li>Please do not collect input from the user. Instead, call ALL the methods of the class with the data you choose to make sure the methods work properly. In the comments explain why you decided to use these particular test cases.</li>

 <li>Have try/catch blocks that handle Illegal Argument Exception. Make sure you write the call that invokes Illegal Argument Exception in main(). In addition, make sure to call class constructors and mutator methods with bad arguments to showcase exception throwing/catching in action.</li>

</ul>

<strong> </strong>