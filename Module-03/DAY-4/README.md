# Ex.No:3(D) STRING TOKENIZER IN JAVA

## AIM:
To create a java program using StringTokenizer class that tokenizes a string "My name is Java Programming" on the basis of whitespace.

## ALGORITHM :
1.	Start the Program
2.	Import `Scanner` and `StringTokenizer` and define class `tok`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Initialize the string `str` as "My name is Java Programming"
4.	Create a `StringTokenizer` object `token` to tokenize `str`
5.	Use a `while` loop to iterate through tokens:
-	a) Print each token using `token.nextToken()`
6.	End




## PROGRAM:
 ```
/*# Ex.No:3(D) STRING TOKENIZER IN JAVA

## AIM:
To create a java program using StringTokenizer class that tokenizes a string "My name is Java Programming" on the basis of whitespace.

## ALGORITHM :
1.	Start the Program
2.	Import `Scanner` and `StringTokenizer` and define class `tok`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Initialize the string `str` as "My name is Java Programming"
4.	Create a `StringTokenizer` object `token` to tokenize `str`
5.	Use a `while` loop to iterate through tokens:
-	a) Print each token using `token.nextToken()`
6.	End




## PROGRAM:
 ```
/*
Program to implement a String Tokenizer using Java
Developed by: KISHORE B
RegisterNumber: 212224100032
*/
```

## Sourcecode.java:
```
import java.util.StringTokenizer;  
public class Simple{  
 public static void main(String args[]){  
   StringTokenizer st = new StringTokenizer("My name is Java Programming"," ");  
     while (st.hasMoreTokens()) {  
         System.out.println(st.nextToken());  
     }  
   }  
}  
```
## OUTPUT:

<img width="463" height="295" alt="Screenshot 2025-10-09 212611" src="https://github.com/user-attachments/assets/a33d29c2-f353-479a-b585-72ac3556b937" />


## RESULT:
Thus the java program using StringTokenizer class that tokenizes a string "My name is Java Programming" on the basis of whitespace was executed successfully.



Program to implement a String Tokenizer using Java
Developed by: 
RegisterNumber:  
*/
```

## Sourcecode.java:







## OUTPUT:



## RESULT:
Thus the java program using StringTokenizer class that tokenizes a string "My name is Java Programming" on the basis of whitespace was executed successfully.

