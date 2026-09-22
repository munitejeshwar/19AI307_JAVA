# Ex.No:2(B) METHODS

## QUESTION:
Write a method void modifyValue(int num) that tries to modify the passed value(add passed value with 10) and print "Inside method: "+num .

Show in main() that the original value does not change.

After calling modifyValue(int num) method in main , print the "Outside method: "+num

## AIM:
To write a Java program that demonstrates how primitive data is passed by value in methods.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3. Define a method modifyValue(int num) that adds 10 to num and prints it.
4.	In main(), declare num and assign a value (e.g., 20).
5.	Call modifyValue(num) to show modification inside the method.
6.	Print the value of num outside the method to show it remains unchanged.
7.	End the program.





## PROGRAM:
 ```
Program to implement a Methods using Java
Developed by: GOKULRAJ K
RegisterNumber:  212225040096
```

## SOURCE CODE:

```
import java.util.Scanner;
class prog {
    public static void modifyValue(int num) {
        num = num + 10;
        System.out.println("Inside method: " + num);
    }

    public static void main(String[] args) {
 Scanner sc = new Scanner(System.in);
        int x = sc.nextInt();
        modifyValue(x);
        System.out.println("Outside method: " + x);
    }
}
```





## OUTPUT:

<img width="1154" height="333" alt="image" src="https://github.com/user-attachments/assets/74c788f6-c707-4fbf-92c1-8c14b3f6ee05" />


## RESULT:
The program successfully shows that primitive data types in Java are passed by value, so changes inside the method don’t affect the original variable.


