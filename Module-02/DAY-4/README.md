# Ex.No:2(D) MULTI-DIMENSIONAL ARRAY

## AIM:
To read and display a 2D array using nested loops.

## ALGORITHM :
1. Start the program and create a Scanner object to take input.

2. Read two integers n1 and n2 to define the dimensions of the 2D array.

3. Declare a 2D array of size n1 x n2.

4. Use nested for loops to read values into the array.

5. Use another set of nested for loops to print the array in matrix format.

## PROGRAM:
 ```
Program to implement a Multi Dimensional Array using Java
Developed by: Vamsi Krishna G
RegisterNumber:  212223220120

import java.util.*;
public class Demo{
    public static void main(String arg[]){
        int n1,n2;
        Scanner sc = new Scanner(System.in);
        n1 = sc.nextInt();
        n2 = sc.nextInt();
        int[][] arr = new int[n1][n2];
        for(int i =0;i<n1;i++){
            for(int j =0;j<n2;j++){
                arr[i][j] = sc.nextInt();
            }
        }
        System.out.println("The Array is :");
        for(int i =0;i<n1;i++){
            for(int j =0;j<n2;j++){
                System.out.print(arr[i][j]+ "  ");
            }
            System.out.println();
        }
    }
}

```

## OUTPUT:

![Screenshot 2025-05-09 114025](https://github.com/user-attachments/assets/7d8a235e-3cb0-4f0c-a582-54e7bf248e50)


## RESULT:
Thus the java program that returns the sum of all the values in a 2D array was executed successfully.


