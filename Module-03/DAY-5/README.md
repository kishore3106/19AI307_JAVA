# Ex.No:3(E)  STRINGBUILDER OBJECT REFERENCE IN JAVA

## AIM:
To write a Java program that creates a StringBuilder object using a given string and assigns its reference to the variable sb.

## ALGORITHM :
1.	Start the program.
2.	Declare and initialize a string variable str1.
3.	Create a StringBuilder object by passing str1 to its constructor.
4.	Store the object reference in the variable sb.
5.	Print the contents of sb to verify the output.
6.	End the program.


## PROGRAM:
 ```
/*
Program to implement a StringBuilder Object Reference in Java
Developed by: KISHORE B
RegisterNumber: 212224100032  
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

public class StringBuilderExample {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        String str1 = scanner.nextLine();

        StringBuilder sb = new StringBuilder(str1);

        System.out.println(sb.length());
        System.out.println( (sb.length() + 16));
    }
}
```
## OUTPUT:

<img width="428" height="365" alt="Screenshot 2025-10-09 212750" src="https://github.com/user-attachments/assets/3bc7a1f4-a1d7-4756-8ff0-4faf81d4347d" />


## RESULT:
Thus the  Java program successfully creates a StringBuilder object using the given string and stores the reference in the variable sb. The contents of the object are printed using the reference variable.

