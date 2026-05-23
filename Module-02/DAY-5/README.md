# Ex.No:2(E) Array Input

## AIM:
To read and display elements of four integer arrays using user input in Java.
## ALGORITHM :
1. Initialize Scanner and declare four integer arrays of size 2.
2. Prompt the user to input 2 elements for the first array and print each element with its index.
3. Repeat the input and print process for the second array.
4. Repeat the input and print process for the third array.
5. Repeat the input and print process for the fourth array.

## PROGRAM:
 ```
Program to implement a Smallest Element in an Array
Developed by: Vamsi Krishna G
RegisterNumber:  212223220120

import java.util.*;
public class Demo{
    public static void main(String args[]){
        Scanner sc = new Scanner(System.in);
        int[] arr1 = new int[2];
        int[] arr2 = new int[2];
        int[] arr3 = new int[2];
        int[] arr4 = new int[2];
        
        
        System.out.println("Elements of array 1:");
        for(int i=0;i<2;i++){
            arr1[i] = sc.nextInt();
            System.out.println("Index: "+ i +", Value: "+arr1[i]);
        }
        System.out.println("Elements of array 2:");
        for(int i=0;i<2;i++){
            arr2[i] = sc.nextInt();
            System.out.println("Index: "+ i +", Value: "+arr2[i]);
        }
        System.out.println("Elements of array 3:");
        for(int i=0;i<2;i++){
            arr3[i] = sc.nextInt();
            System.out.println("Index: "+ i +", Value: "+arr3[i]);
        }
        System.out.println("Elements of array 4:");
        for(int i=0;i<2;i++){
            arr4[i] = sc.nextInt();
            System.out.println("Index: "+ i +", Value: "+arr4[i]);
        }
    }
}
```

## OUTPUT:
![Screenshot 2025-05-09 134440](https://github.com/user-attachments/assets/91d1a696-81f6-4b70-aab7-4ffd827dea40)



## RESULT:
Thus the java program to read and display elements of four integer arrays using user input in Java.




