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
-	b) Call `sc.print()` to execute the `print()` method# Ex.No:4(C)    CONSTRUCTOR CHAINING(SUPER KEYWORD)

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
Developed by: KISHORE B
RegisterNumber: 212224100032
*/
```

## Sourcecode.java:
```
// Base class Vehicle
class Vehicle {
    // Constructor for Vehicle
    Vehicle() {
        System.out.println("I am a Vehicle");
    }
}

// Derived class Car that extends Vehicle
class Car extends Vehicle {
    // Constructor for Car
    Car() {
        // Call the constructor of Vehicle
        super();
        System.out.println("I am a Car");
    }
}

// Main class to test the implementation
public class Main {
    public static void main(String[] args) {
        // Create an instance of Car
        Car car = new Car();
    }
}
```
## OUTPUT:

<img width="499" height="196" alt="Screenshot 2025-10-09 213540" src="https://github.com/user-attachments/assets/ddba4f95-24a9-4f84-9e71-4cbc54283901" />


## RESULT:
Thus the java program for constructor chaining was executed successfully.



5.	End







## PROGRAM:
 ```
/*
Program to implement a Constructor Chaining using Java
Developed by: 
RegisterNumber:  
*/
```

## Sourcecode.java:







## OUTPUT:



## RESULT:
Thus the java program for constructor chaining was executed successfully.





