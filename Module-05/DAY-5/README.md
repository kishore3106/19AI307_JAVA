# Ex.No:5(E) HAS-A RELATIONSHIP
## AIM:
To implement a  Java Program to Find the Largest or Max Number in Array using has - a relationship.
## ALGORITHM :
1.	Start the program.
2.	Create a class ArrayData:
a.	Declare an integer array and a variable for size.
b.	Create a method to read array elements from the user.
3.	Create another class ArrayOperation:
a.	Create a method findMax() that accepts an ArrayData object.
b.	Loop through the array and find the largest element.
4.	In the main() method of a class Main:
a.	Create an object of ArrayData and read the input.
b.	Create an object of ArrayOperation and call findMax() by passing the ArrayData object.
5.	Display the largest number.
6.	End the program.



## PROGRAM:
 ```
/*
Program to implement a HAS-A RelationShip
Developed by: KISHORE B
RegisterNumber: 212224100032  
*/
```

## Sourcecode.java:
```
import java.util.Scanner;
class fun{
    public int largest(int[] array) {
    
    
    int max = array[0];

   
    for (int i = 1; i < array.length; i++) {
      if (max < array[i])
        max = array[i];
    }

    return max;
  }
}
public class ArrayProgram {

  public static void main(String[] args) {
   
    Scanner scan = new Scanner(System.in);

    
    int size = 0;
    int arr[] = null;

   
    size = scan.nextInt();

   
    arr = new int[size];

  
  
    for (int i = 0; i < arr.length; i++) {
      arr[i] = scan.nextInt();
    }
    fun obj=new fun();
   
    System.out.println("Largest element = " + obj.largest(arr));

  }
}
```
## OUTPUT:

<img width="690" height="521" alt="Screenshot 2025-10-09 215149" src="https://github.com/user-attachments/assets/ce7d5a5d-4e67-4a3d-a736-1710aaaaa531" />


## RESULT:
Thus the java program to Find the Largest or Max Number in Array using has - a relationship was executed successfully. 

