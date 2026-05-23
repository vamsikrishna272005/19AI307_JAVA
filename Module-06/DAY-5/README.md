# Ex.No:6(E) Arrays and Looping

## AIM:
To find and display the smallest number in a user-defined array.

## ALGORITHM :

1. Read the size of the array from the user.
2. Create an integer array of the specified size.
3. Read elements into the array using a loop.
4. Initialize a variable with the first element and compare it with the rest to find the smallest.
5. Print the smallest number after the loop ends.

## PROGRAM:
 ```
/*
Program to implement a Multiple Inheritance
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

import java.util.*;
public class Demo{
    public static void main(String ar[]){
        int a;
        Scanner sc = new Scanner(System.in);
        a = sc.nextInt();
        int[] arr = new int[a];
        for(int i =0;i<a;i++){
            arr[i] = sc.nextInt();
        }
        int lar = arr[0];
        for(int i =0;i<a;i++){
            if(lar> arr[i]){
                lar = arr[i];
            }
        }
        System.out.println("Smallest Number = "+lar);
    }
}
*/
```
## OUTPUT:

![Screenshot 2025-05-10 060806](https://github.com/user-attachments/assets/d67426d4-de06-467b-9d38-971dd45e6d06)


## RESULT:

Thus, the java program To find and display the smallest number in a user-defined array executed successfully.
