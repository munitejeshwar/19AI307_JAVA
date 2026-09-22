# Ex.No:3(B) STRING BUFFER IN JAVA

## AIM:
To develop a java program use append() method concatenates the given argument with this String and use stringbuffer class.

## ALGORITHM :
1.	Start the program.
2.	Import `Scanner` and define class `concat`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read two strings `a` and `b` from user input
4.	Create a `StringBuffer` object `sb` initialized with string `a`
5.	Append a space and string `b` to `sb`
6.	Print the concatenated result from `sb`
7.	End
## PROGRAM:
 ```
/*
Program to implement a String Buffer using Java
Developed by: SANTHOSH V
RegisterNumber: 212224230252
*/
```

## Sourcecode.java:

```
import java.util.*;
	    
		
	public class Assignment6 {

	public static void main(String[] args) {
		Scanner sc=new Scanner(System.in);
		String a =sc.nextLine();
		String b =sc.nextLine();
		String output;

		if (a.length() < b.length()) 
			output = a + b + a;
		else
			output = b + a + b;
		
		System.out.println(output);
	}

}
```
## OUTPUT:

<img width="396" alt="Image" src="https://github.com/user-attachments/assets/6d1b7a6e-8a82-4e5e-86cb-5b7d741f077a" />

## RESULT:
Thus the java program use append() method concatenates the given argument with this String and use stringbuffer class was executed successfully.
