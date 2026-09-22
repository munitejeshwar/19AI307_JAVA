# Ex.No:2(C)    SINGLE ARRAY

## AIM:
To create a java program to read 5 values and display the all 5 values from array using single dimensional array.

## ALGORITHM :
1.	Start the program.
2.	2.	Import the `Scanner` class from the `java.util` package
3.	Define a class named `ArrayExample`
4.	Inside the `main` method:
-	a) Create a `Scanner` object called `scanner` to take user input
-	b) Declare an integer array `values` of size 5
-	c) Use a `for` loop to iterate from `i = 0` to `i < 5`:
-   d) Take input from the user and store it in `values[i]`
5.	Print "Elements in Array are :"
6.	Use another `for` loop to iterate from `i = 0` to `i < 5`:
-	a) Print each element in `values` followed by a space
7.	Close the `scanner` to release resources
8.	End





## PROGRAM:
 ```
/*
Program to implement a Single Array using Java
Developed by: SANTHOSH V
RegisterNumber: 212224230252
*/
```

## Sourcecode.java:
```

import java.util.*;

public class Main
{
   public static void main(String args[])
   {    

	Scanner sc=new Scanner(System.in);
	
	int a[]=new int[5];//declaration    	 
	
        for(int i=0; i<5; i++)
        {
           a[i] = sc.nextInt();
        }   
        System.out.print("Elements in Array are :\n");
        for(int i=0; i<5; i++)
        {
           System.out.print(a[i] + "  ");
        }  
   }
}
	


```






## OUTPUT:
```
Input       Expected                                  Got

3           Elements in Array are :                   Elements in Array are :                   
            3  4  5  6  7                             3  4  5  6  7
4
5
6
7


```


## RESULT:
Thus, the Java program Thus the java program to read 5 values and display the all 5 values from array using single dimensional  was executed successfully.


