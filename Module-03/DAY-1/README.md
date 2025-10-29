# Ex.No:3(A)  STRING AND ITS OPERATIONS IN JAVA
## AIM:
To create a java program to read input and print length of the string in java.

## ALGORITHM :
1.  Start the Program.
2.	Import `Scanner` and define class `demo`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read a line of text into `String` variable `str`
4.	Print "The size of the String is " + `str.length()`
5.	End




## PROGRAM:
 ```
/*
Program to implement a String and its Operations using Java
Developed by: KISHORE B
RegisterNumber: 212224100032
*/
```

## Sourcecode.java:
```
import java.util.Scanner;
public class Main {
	public static void main(String[] args)
	{
    	// Here str is a string object
   	Scanner sc = new Scanner(System.in);  // Create a Scanner object
   	String str = sc.nextLine();

 
    	System.out.println(
        	"The size of "
        	+ "the String is "
        	+ str.length());
	}
}
```
## OUTPUT:

<img width="883" height="291" alt="Screenshot 2025-10-09 205825" src="https://github.com/user-attachments/assets/9ef1f684-aac9-4e29-a3f0-d80e72e32f99" />


## RESULT:
Thus the java Program to read input and print length of the string in java was executed successfully.



