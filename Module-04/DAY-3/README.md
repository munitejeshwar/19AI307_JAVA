# Ex.No:4(C)    CONSTRUCTOR CHAINING(SUPER KEYWORD)

## AIM:
To Create a Java program to implement super keyword in constructor.

## ALGORITHM :
1.  Start the Program.
2.	Define class `College`:
-	a) Define method `display()` that prints "I am a Vehicle"
3.	Define class `Student` that extends `College`:
-	a) Override method `display()` to print "I am a Car"
-	b) Define method `print()`:
-	i) Call `super.display()` to invoke `display()` from `College` class
-	ii) Call `this.display()` to invoke `display()` from `Student` class
4.	Define `Main` class with `main` method:
-	a) Create a `Student` object `sc`
-	b) Call `sc.print()` to execute the `print()` method
5.	End







## PROGRAM:
 ```
/*
Program to implement a Constructor Chaining using Java
Developed by: SANTHOSH V
RegisterNumber: 212224230252
*/
```

## Sourcecode.java:


```
class Parent {
  void display(){
    System.out.println("I am a Bird");
  }
}

class Child extends Parent{

  public void  display(){
    System.out.println("I am a Parrot");
  }

  public void print(){

    
    this.display();

    super.display();
  }
}

public class Main {
  public static void main(String[] args) {
    Child obj = new Child();
    obj.print();
  }
}
```




## OUTPUT:
<img width="526" alt="Image" src="https://github.com/user-attachments/assets/4acb3b1c-abc0-4bf7-a945-71cfde631a61" />


## RESULT:
Thus the java program for constructor chaining was executed successfully.




