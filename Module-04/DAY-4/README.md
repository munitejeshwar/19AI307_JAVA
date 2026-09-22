# Ex.No:4(D) FINAL & STATIC IN JAVA

## AIM:
   To create a Java program to perform final & static keyword for below situation Employee object contains member 'Emp_Id'. It contains object named name, which contains its own informations such as Fname, Mname, Lname.
 
## ALGORITHM :
1.	Start the Program.
2.	Define class `Name`:
-	a) Declare three `String` variables: `Fname`, `Mname`, and `Lname`
-	b) Define method `dispName(String fn, String mn, String ln)`:
-	i) Print the full name using the passed parameters `fn`, `mn`, and `ln`
3.	Define class `Employee`:
-	a) Declare an integer variable `Emp_Id`
-	b) Create an instance of `Name` called `obj`
-	c) Define method `disp(int id)`:
-	i) Print the employee ID
-	ii) Create a new `Name` object and call `dispName("B", "Leo", "John")` to display the name
4.	Define `Main` class with `main` method:
-	a) Create an `Employee` object `emp`
-	b) Call `emp.disp(101)` to display the employee details
5.	End






## PROGRAM:
 ```
/*
Program to implement a final & Static using Java
Developed by: SANTHOSH V
RegisterNumber: 212224230252
*/
```

## Sourcecode.java:

```
final class Student {
    String Name;
    String Id;
    final String Year = "3th Year"; // Final variable with a fixed value

    // Constructor to initialize Name and Id
    Student(String Name, String Id) {
        this.Name = Name;
        this.Id = Id;
    }

    // Method to display the details
    void print() {
        System.out.println("Student Details are,");
        System.out.println("Id is " + Id);
        System.out.println("Name is " + Name);
        System.out.println("Year of Studying is " + Year);
    }
}

// Main class to test the functionality
public class Main {
    public static void main(String[] args) {
        // Create an instance of Student class with given Name and Id
        Student student = new Student("David", "S201");

        // Call the print method to display the details
        student.print();
    }
}

```





## OUTPUT:
<img width="558" alt="Image" src="https://github.com/user-attachments/assets/02e296c7-1a4b-4abf-87bd-cd67d25cc525" />


## RESULT:
Thus, the java program to perform final & static keyword was executed successfully.
