# Ex.No:1(D) USER DEFINED METHOD.

## AIM:
To write a Java program to calculate and print the area of a circle by defining an instance method and using local variables. The class name is Area, the method name is calculateArea(), and the return type is void.

## ALGORITHM :
1. Start the program.

2. Import the `java.util` package.

3. Define a class named `Area`.

4. Declare an instance method named `calculateArea()` with return type `void`.

5. Inside the method:
   
   a) Create a `Scanner` object to read user input.
   
   b) Declare local variables `radius` and `cirarea`.
   
   c) Read the radius value from the user.
   
   d) Calculate the area using the formula `3.14 * radius * radius`.
   
   e) Print the calculated area.

6. In the `main` method:
   
   a) Create an object of the `Area` class.
   
   b) Call the `calculateArea()` method using the object.

7. End the program.





## PROGRAM:
 ```
/*
Program to implement a User Defined Method using Java
Developed by: SANTHOSH V
RegisterNumber: 212224230252
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
![image](https://github.com/user-attachments/assets/ed252e49-6612-47ca-b513-113432021f3c)

## RESULT:
Thus, the Java program to calculate the area of a circle using an instance method and local variables with a void return type is successfully created and executed.
