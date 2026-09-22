# Ex.No:1(E)  STATIC VARIABLE

## AIM:
To write a Java program that determines whether a given number is odd or even using a static method. The input number is passed directly to the method, and the result is printed using simple conditional logic.

## ALGORITHM :
1. Start the program.

2. Define a class named `Main`.

3. In the `main()` method:
   a) Declare an integer variable `num` and assign it the value `7`.
   b) Call the static method `find_Oddeven(num)` and pass `num` as an argument.

4. Define a static method named `find_Oddeven(int num)`:
   a) Check if `num % 2 == 0`.
      - If true, print "`num` is even".
      - Otherwise, print "`num` is odd".

5. End the program.


## PROGRAM:
 ```
/*
Program to implement a Static Variable using Java
Developed by: SANTHOSH V
RegisterNumber: 212224230252
*/
```

## Sourcecode.java:
```
import java.util.Scanner;
public class Main{
public static void main (String[] args){
int num=7;
find_Oddeven(num);
}

static void find_Oddeven(int num){
  if(num%2==0) 
      System.out.println(num+" is even"); 
  else 
      System.out.println(num+" is odd");
 }
}
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/8f7cdb15-9d19-4cc3-8d20-2c0a25af9899)

## RESULT:
Thus, the Java program to check whether a number is odd or even using a static method with a fixed input value (7) is successfully created and executed.
