# Ex.No:2(E)  SMALLEST ELEMENT IN AN ARRAY

## AIM:
To write a Java program that reads an array size and elements from the user and then finds and prints the smallest element in the array.
## ALGORITHM :
1.	Start the program.
2.	Read the size of the array from the user.
3.	Declare an array of the given size.
4.	Read the array elements from the user.
5.	Initialize a variable min with the first element of the array.
6.	Traverse the array using a loop.
7.	Compare each element with min. If an element is smaller, update min.
8.	After the loop ends, print the smallest number.
9.	End the program.
	

## PROGRAM:
 ```
/*
Program to implement a Smallest Element in an Array
Developed by: KISHORE B
RegisterNumber: 212224100032 
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main
{
    public static void main(String[]args)
    {
        Scanner in=new Scanner(System.in);
        int size=in.nextInt();
        int array[]=new int[size];
        for(int i=0;i<size;i++)
        {
            array[i]=in.nextInt();
        }
        int small=array[0];
        for(int i=0;i<size;i++)
        {
            if(array[i]<small)
            {
                small=array[i];
            }
        }
        System.out.print("Smallest Number = "+small);
    }
}
```
## OUTPUT:

<img width="900" height="769" alt="Screenshot 2025-10-09 205449" src="https://github.com/user-attachments/assets/82494224-53df-421a-a236-3e39d94891f3" />


## RESULT:
Thus the java program successfully reads the array size and elements from the user and correctly finds and prints the smallest number in the array.



