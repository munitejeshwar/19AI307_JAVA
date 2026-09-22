# Ex.No:3(A)  STRING AND ITS OPERATIONS IN JAVA
## AIM:
To create a java program to read input and print length of the string in java.

## ALGORITHM :
1.Start the program.

2.Define a class named Addition.

3.Declare two private integer variables, num1 and num2.

4.Define a private method add() that:
a)  Returns the sum of num1 and num2.

5.Define a public method display(int n1, int n2) that:
a)  Assigns n1 to num1 and n2 to num2.
b)  Calls the add() method and prints the result using System.out.println.

6Define the main method as static.
a)  Create an instance of the Addition class called ad.
b)  Call the display(8, 9) method on the ad object.

7.End the program.

## PROGRAM:
 ```
/*
Program to implement a String and its Operations using Java
Developed by: SANTHOSH V
RegisterNumber: 212224230252
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

public class StringEqualityCheck {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        
        
        String string1 = scanner.nextLine();

       
        String string2 = scanner.nextLine();

        
        boolean areEqual = string1.equals(string2);

       
        System.out.println(areEqual);

        scanner.close();
    }
}
```

## OUTPUT:
<img width="513" alt="IMG1" src="https://github.com/user-attachments/assets/efe35baa-fdd2-4dea-a602-c54201aee16d" />

## RESULT:
Thus the java Program to read input and print length of the string in java was executed successfully.

