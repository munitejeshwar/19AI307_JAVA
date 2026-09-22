# Ex.No:4(B) INTRODUCTION TO JAVA INHERITANCE

## AIM:
To create  a Java program to perform the inheritance concept for employee details.

## ALGORITHM :
1.	Start the Program
2.	Define class `Person`:
-	a) Declare `emp_id`, `name`, and `dept` as instance variables
3.	Define class `Employee` that extends `Person`:
-	a) Define method `getDetails()`:
-	i) Create a `Scanner` object `sc`
-	ii) Read `name`, `emp_id`, and `dept` from user input
-	b) Define method `display()`:
-	i) Print the `name`, `emp_id`, and `dept`
4.	Define `Main` class with `main` method:
-	a) Create an `Employee` object `emp`
-	b) Call `getDetails()` to input employee details
-	c) Call `display()` to output employee details
5.	End








## PROGRAM:
 ```
/*
Program to implement a Inheritance using Java
Developed by: SANTHOSH V
RegisterNumber: 212224230252
*/
```

## Sourcecode.java:
```

import java.util.Scanner;
class Employee 
{
    int id;
    String dept;
    void getDetails()
    {
       Scanner sc=new Scanner(System.in);
       id=sc.nextInt();
       dept=sc.next();
    }
}
class Manager extends Employee
{
    void display()
    {
        int salary=35000;
        System.out.println("Emp_ID: "+id+" Department: "+dept+" Salary: "+salary);
    }
}
public class Main
{
    public static void main(String[] args)
    {
       Manager obj = new Manager();
       obj.getDetails();
       obj.display();
    }
}

```



## OUTPUT:

<img width="518" alt="Image" src="https://github.com/user-attachments/assets/1911eabd-84ed-4cfd-a167-cf18253126c5" />

## RESULT:
Thus the Java program to implement the inheritance concept for employee details was  executed successfully.

