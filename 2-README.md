# Ex.No:2(A)  STATIC METHOD

## AIM:
To calculate and display the area of a circle using a method.

## ALGORITHM :
1. Start the program and create a Scanner object for input.

2. Read the radius r as a double from the user.

3. Call the method calculateArea(r) to compute the area by squaring the radius.

4. Store and print the returned value with the message (currently labeled as "Area of square").

5. Close the scanner and end the program.


## PROGRAM:
 ```
Program to implement a Static method using Java
Developed by: Vamsi Krishna G
RegisterNumber:  212223220120

import java.util.Scanner;

public class AreaOfCircleMethod 

{
   public static void main(String[] args) 
   {
      Scanner sc = new Scanner(System.in);
      double r = sc.nextInt();
      double area = calculateArea(r);
      System.out.println("Area of square : " + area);
      sc.close();
   }

   static double calculateArea(double r)
   {
      return ( r * r);
   }
}
```

## OUTPUT:

![Screenshot 2025-05-09 112302](https://github.com/user-attachments/assets/5280fe7c-0aee-4bc4-b648-72f4ff8e7892)


## RESULT:
Thus , To calculate and display the area of a circle using a method is done successfully.


# Ex.No:2(B) ACCESS MODIFIERS

## AIM:
To print all numbers divisible by 7 from 100 to 1 in descending order.

## ALGORITHM :
1. Start the program and define the main method.

2. Use a for loop starting from 100 down to 1.

3. For each number i, check if it is divisible by 7 (i % 7 == 0).

4. If the condition is true, print the number followed by a comma.

5. Continue the loop until i reaches 1, then end the program.
## PROGRAM:
 ```

Program to implement a access modifiers using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

import java.util.*;
public class Demo{
    public static void main(String args[]){
        for(int i =100 ;i>=1;i--){
            if(i%7==0){
            System.out.print(i+", ");
            }
        }
    }
}

```

## OUTPUT:

![Screenshot 2025-05-09 112905](https://github.com/user-attachments/assets/b77422a6-b070-4ddd-9963-ea3ce73dc46f)


## RESULT:
Thus the java program to print all numbers divisible by 7 from 100 to 1 in descending order is done successfully.



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




