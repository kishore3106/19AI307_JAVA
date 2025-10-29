# Ex.No:3(C)    STRING BUILDER IN JAVA

## AIM:
To Create a java program use replace() method replaces the given String from the specified beginIndex and endIndex and use stringbuilder

## ALGORITHM :
1.  Start the Program
2.	Import `Scanner` and define class `replace`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read a string `str` from user input
4.	Create a `StringBuilder` object `sb` initialized with `str`
5.	Use the `replace()` method to replace characters from index 1 to 3 with "Java"
6.	Print the modified string using `sb.toString()`
7.	End






## PROGRAM:
 ```
/*
Program to implement a String Builder using Java
Developed by: KISHORE B
RegisterNumber: 212224100032
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

public class StringLength {
    public static void main(String[] args) {
        // Create a Scanner object to read input
        Scanner scanner = new Scanner(System.in);

        String input = scanner.nextLine();

        // Create a StringBuilder object with the input string
        StringBuilder sb = new StringBuilder(input);

        // Get the length of the string
        int length = sb.length();

        // Output the result
        System.out.println("The size of the String is " + length);

        // Close the scanner
        scanner.close();
    }
}
```
## OUTPUT:

<img width="876" height="226" alt="Screenshot 2025-10-09 210318" src="https://github.com/user-attachments/assets/def49de1-f5b8-4fb6-95fe-f8cd235ceb04" />


## RESULT:
Thus the java program use replace() method replaces the given String from the specified beginIndex and endIndex and use stringbuilder was executed successfully.





