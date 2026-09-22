# Ex.No:5(A)  DATA HIDING AND ENCAPSULATION
## AIM:
To Create a java program to display name and location of the employee and use the encapsulation concepts

## ALGORITHM :
1.  Start the program
2.	Define class `Employee`:
-	a) Declare two private `String` variables: `name1` and `name2`
-	b) Define `setname(String n1)` method to set `name1` to `n1`
-	c) Define `setname2(String n2)` method to set `name2` to `n2`
-	d) Define `get1()` method to return `name1`
-	e) Define `get2()` method to return `name2`
3.	Define `Main` class with `main` method:
-	a) Create `Scanner` object `sc` for input
-	b) Read `name1` and `name2` from user input
-	c) Create ` Employee ` object `hl`
-	d) Use `hl.setname(name1)` and `hl.setname2(name2)` to set the names
-	e) Print the values of `hl.get1()` and `hl.get2()`
4.	End





## PROGRAM:
 ```
/*
Program to implement a Data Hiding & Encapsulation using Java
Developed by: SANTHOSH V
RegisterNumber: 212224230252
*/
```

## Sourcecode.java:

```
import java.util.*;
public class java{
    private long a;
    void set(long x)
    {
        this.a=x;
    }
    void get()
    {
        System.out.println(this.a);
    }

public static void main(String[] args)
{
    java j=new java();
    Scanner s=new Scanner(System.in);
    long l=s.nextLong();
    j.set(l);
    j.get();
    
    
}
}
```





## OUTPUT:
<img width="538" alt="Image" src="https://github.com/user-attachments/assets/bac8da47-50db-490a-bad8-d21aabcb06ba" />


## RESULT:
Thus , the  java program to display name and location of the employee and use the encapsulation concepts executed successfully.
