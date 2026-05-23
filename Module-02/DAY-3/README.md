# Ex.No:2(C)    SINGLE ARRAY

## AIM:
 To read and display a list of strings using a do-while loop.

## ALGORITHM :
1. Start the program and create a Scanner object for input.

2. Read an integer n from the user to determine the array size.

3. Create a String array of size n and read n strings into the array.

4. Initialize a counter i = 0 and use a do-while loop to print each string.

5. Increment the counter and continue printing until all elements are displayed, then end the program.
## PROGRAM:
 ```

Program to implement a Single Array using Java
Developed by: Vamsi Krishna G
RegisterNumber:  212223220120

import java.util.*;
public class Demo{
    public static void main(String args[]){
        int n;
        Scanner sc = new Scanner(System.in);
        n = sc.nextInt();
        String arr[] = new String[n];
        System.out.println("Entered characters are:");
        for(int i =0;i<n;i++){
            arr[i] = sc.next();
        }
        int i =0;
        do{
            System.out.println(arr[i]);
            i++;
        }while(i<n);
    }
}

```

## OUTPUT:

![Screenshot 2025-05-09 113652](https://github.com/user-attachments/assets/4a1f4054-9536-4704-b339-8a03957bcb81)


## RESULT:
Thus, the Java program to read and display a list of strings using a do-while loop.


