# Ex.No:7(B) EXCEPTION HANDLING-FINALLY
## AIM:
To illustrate the use of `try-catch-finally` in handling an `ArrayIndexOutOfBoundsException`.
## ALGORITHM :
1. Create an integer array of size 4.
2. Attempt to access the 5th element (index 4), which causes an `ArrayIndexOutOfBoundsException`.
3. Catch the exception and print a relevant message inside the `catch` block.
4. Execute the `finally` block regardless of whether an exception occurred.
5. Continue program execution and print a message outside the `try-catch-finally` structure.

## PROGRAM:
 ```
/*
Program to implement a Exception Handling-Finally using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

import java.util.*;
public class HelloWorld {
    public static void main(String[] args) 
    {

        int[] arr = new int[4];
         
        try
        {
            int i = arr[4];
            System.out.println("Inside try block");
        }
         
        catch(ArrayIndexOutOfBoundsException ex)
        {
            System.out.println("Exception caught in catch block");
        }
         
        finally
        {
            System.out.println("finally block executed");
        }
        System.out.println("Outside try-catch-finally clause");
    }
}
      
*/
```

## OUTPUT:

![Screenshot 2025-05-10 061345](https://github.com/user-attachments/assets/733d0dee-697a-4148-92fd-8f0c4258c677)


## RESULT:
Thus the Java program To illustrate the use of `try-catch-finally` in handling an `ArrayIndexOutOfBoundsException` executed successfully.



