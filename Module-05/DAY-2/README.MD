# Ex.No:5(B) TIGHTLY ENCAPSULATED CLASS

## AIM:
To Create a java program to display the value of volume of cylinder get the radius and height value as input and use tightly encapsulated class.

## ALGORITHM :
1.	Start the program.
2.	Define `Cylinder` class:
-	a) Private variables `radius` and `height`
-	b) `setRadius(int r)` and `setHeight(int h)` methods to set values
-	c) `getVolume()` method:
- i) Calculate and print `volume = pi * radius * radius * height`
3.	In `Main` class `main` method:
-	a) Use `Scanner` to read `radius` and `height`
-	b) Create `Cylinder` object, set values, and call `getVolume()`
4.	End
## PROGRAM:
 ```
/*
Program to implement a tightly encapsulated class using Java
Developed by: Santhosh v
RegisterNumber: 212224230252
*/
```

## Sourcecode.java:
```
import java.util.*;
public class SetAndGet {
private String a;
private String b;

public void getadd() {
    int a1=Integer.parseInt(a);
    int b1=Integer.parseInt(b);
	System.out.print("Sum is " + (a1+b1)); 
	
}
public void setadd(String a,String b) {
 this.a =a;
 this.b=b;
}

public static void main(String args[]){
 Scanner sc=new Scanner(System.in);
 SetAndGet obj = new SetAndGet();
 String str=sc.nextLine();
 String str1=sc.nextLine();
 
 obj.setadd(str,str1);
 
 obj.getadd();
}
}
```





## OUTPUT:
<img width="538" alt="Image" src="https://github.com/user-attachments/assets/00b65b79-c858-471f-ad94-f6f11a4342bc" />


## RESULT:
Thus a java program to display the value of volume of cylinder get the radius and height value as input and use tightly encapsulated class was executed successfully.



