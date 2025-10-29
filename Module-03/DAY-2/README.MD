# Ex.No:3(B) STRING BUFFER IN JAVA

## AIM:
To develop a java program use append() method concatenates the given argument with this String and use stringbuffer class.

## ALGORITHM :
1.	Start the program.
2.	Import `Scanner` and define class `concat`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read two strings `a` and `b` from user input
4.	Create a `StringBuffer` object `sb` initialized with string `a`
5.	Append a space and string `b` to `sb`
6.	Print the concatenated result from `sb`
7.	End







## PROGRAM:
 ```
/*
Program to implement a String Buffer using Java
Developed by: KISHORE B
RegisterNumber: 212224100032  
*/
```

## Sourcecode.java:
```
import java.util.*;
public class StringBufferExample3{  
    public static void main(String args[]){ 
        Scanner sc=new Scanner(System.in);
        String str1=sc.nextLine();
        StringBuffer sb=new StringBuffer(str1);  
        sb.replace(1,3,"Java");  
        System.out.println(sb); 
}  
}  
```
## OUTPUT:



## RESULT:

Thus the java program use append() method concatenates the given argument with this String and use stringbuffer class was executed successfully.



