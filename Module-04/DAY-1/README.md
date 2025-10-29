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
Developed by: KISHORE B
RegisterNumber: 212224100032
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

// Base class
class Employee {
    String name;
    int empID;

    void setDetails(String name, int empID) {
        this.name = name;
        this.empID = empID;
    }

    void displayDetails() {
        System.out.print("Name: " + name);
        System.out.print("Emp_ID: " + empID);
    }
}

// Derived class
class Department extends Employee {
    String departmentName;

    void setDepartment(String departmentName) {
        // If the input is "Software Developer", we abbreviate it to "Software"
        if (departmentName.equalsIgnoreCase("Software Developer")) {
            this.departmentName = "Software";
        } else {
            this.departmentName = departmentName;
        }
    }

    void displayDepartmentDetails() {
        // Call the base class method to display name and empID
        displayDetails();
        System.out.println("Department: " + departmentName);
    }
}

// Main class
public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Creating an object of the Department class
        Department employee = new Department();

        // Getting user input
        String name = scanner.nextLine();
        int empID = scanner.nextInt();
        scanner.nextLine();  // Consume the newline l;
        String department = scanner.nextLine();

        // Setting and displaying employee and department details
        employee.setDetails(name, empID);
        employee.setDepartment(department);
        employee.displayDepartmentDetails();
    }
}
```
## OUTPUT:



## RESULT:
Thus the Java program to implement the inheritance concept for employee details was  executed successfully.

# Ex.No:4(A)  JAVA CONSTRUCTOR
## AIM:
To create a Java program using constructor to print the circumference of rectangle.[l=5,w=6]

## ALGORITHM :
1.  1.	Start the Program.
2.	Define a class `circum`
3.	Inside the class, define two integer variables `l` and `w` with values 5 and 6, respectively
4.	Create a constructor `circum()`:
-	a) Calculate the `circumference` as `2 * (l + w)`
-	b) Print the `circumference` twice with different labels ("Area of First Rectangle" and "Area of Second Rectangle")
5.	In `main`, create an object `sc` of the `circum` class
6.	End





## PROGRAM:
 ```
/*
Program to implement a Constructor using Java
Developed by: KISHORE B
RegisterNumber: 212224100032 
*/
```

## Sourcecode.java:
```
class Rectangle 
 { 
    int length;
    int width;
    Rectangle (int l, int w) 
    {  
        //Write your code here
        length=l;
        width=w;
    } 
    Rectangle (Rectangle obj) 
    { 
        //Write your code here
        this.length=obj.length;
        this.width=obj.width;
        
    } 
    int circumference () 
    { 
        //Write your code here
        return (length+width)*2+8;
    } 
} 
    //class to create Rectangle object and calculate area 
public class CopyConstructor 
{ 
    public static void main(String[] args) 
    { 
        Rectangle  firstRect = new Rectangle (5,6); 
        //Write your code here
        System.out.println("Area  of First Rectangle : "+firstRect.circumference());
        Rectangle secondRect = new Rectangle (firstRect);
        System.out.println("Area of First Second Rectangle : "+secondRect.circumference());
    } 
} 
```
## OUTPUT:

<img width="963" height="204" alt="Screenshot 2025-10-09 213003" src="https://github.com/user-attachments/assets/0dee3375-9d40-4dc5-80c1-4b508cac5033" />


## RESULT:
Thus the Java program using constructor to print the circumference of rectangle was executed successfully.


