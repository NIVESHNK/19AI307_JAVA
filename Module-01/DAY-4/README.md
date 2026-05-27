# Ex.No:1(D) USER DEFINED METHOD.

## AIM:
To create a Java program print area of rectangle by defining instance method and local variable value as 10,20 .[Class Name is ‘Area’ function name is ‘calculateArea()’ and return type of function is ’void’

## ALGORITHM :
1.	Start the program.
2.	Define a class named 'Area'
3.	Declare a public method named 'calculateArea' with no parameters
4.	Inside the 'calculateArea' method:
a)	Declare a Double variable 'length' and assign it the value 10.0
b)	Declare a Double variable 'width' and assign it the value 20.0
c)	Calculate the area by multiplying 'length' and 'width' and store the result in a Double variable 'area'
d)	Print the calculated area using the System.out.println statement
5.	Define the 'main' method as static
6.	Inside the 'main' method:
a)	Create an instance of the 'Area' class called 'rectangle'
b)	Call the 'calculateArea' method on the 'rectangle' object




## PROGRAM:
 ```
/*
Program to implement a User Defined Method using Java
Developed by: NIVESH N K
RegisterNumber:  212224050027
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Area {
        double calculateArea()
    {
        double radius,cirarea;
        Scanner sc=new Scanner(System.in);
        radius=sc.nextDouble();
        cirarea=3.14*radius*radius;
        return cirarea;
    }
        public static void main(String[] args) {
       Area obj=new Area();
       double area=obj.calculateArea();
       System.out.println("Area of Circle is "+area);
    }
}
```






## OUTPUT:
<img width="823" height="329" alt="image" src="https://github.com/user-attachments/assets/2ff0cc43-f745-4a06-97c3-a47289ffa0da" />



## RESULT:
Thus, the Java program to print area of rectangle by defining instance method and local variable value as 10,20 was created successfully.

