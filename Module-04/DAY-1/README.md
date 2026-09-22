# Ex.No:4(A)  JAVA CONSTRUCTOR
## AIM:
To create a Java program using constructor to print the circumference of rectangle.[l=5,w=6]

## ALGORITHM :
1. Start the Program.
2.	Define a class `circum`
3.	Inside the class, define two integer variables `l` and `w` with values 5 and 6, respectively
4.	Create a constructor `circum()`:
-	a) Calculate the `circumference` as `2 * (l + w)`
-	b) Print the `circumference` twice with different labels ("Area of First Rectangle" and "Area of Second Rectangle")
5.	In `main`, create an object `sc` of the `circum` class
6.	End
## PROGRAM:
 ```
/*
Program to implement a Constructor using Java
Developed by: SANTHOSH V
RegisterNumber: 212224230252
*/
```

## Sourcecode.java:
```
import java.util.*;
class Car 
{
	String brand;
    Car(String a)
    {
        brand = a;
	}
	public String getBrand() 
	{
	    return (brand);
	}
}
public class Sample 
{
	public static void main(String[] args) 
	{
        Car l = new Car("Apple");
        System.out.print(l.getBrand());
	}
}

```


## OUTPUT:

<img width="491" alt="Image" src="https://github.com/user-attachments/assets/51c5ce08-5f9a-414d-879b-d7223ac041bd" />

## RESULT:
Thus the Java program using constructor to print the circumference of rectangle was executed successfully.
