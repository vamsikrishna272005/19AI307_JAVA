# Ex.No:7(A)           EXCEPTION HANDLING-RUN TIME EXCEPTION
## AIM:
  To demonstrate the use of nested try-catch blocks and finally in Java exception handling.

## ALGORITHM :

1. Read two integers `a` and `b` using `Scanner`.
2. Use a nested `try` block to check for division by zero and throw an `ArithmeticException` if `b == 0`.
3. Catch the exception, display a message, and return from the method if an error occurs.
4. Use another nested `try` block to simulate a `NullPointerException` by calling `.length()` on a null string.
5. Ensure that the `scanner` is closed in the `finally` block regardless of exceptions.



## PROGRAM:
 ```
/*
Program to implement a Exception Handling-Run Time Exception using Java
Developed by: Vamsi Krishna G
RegisterNumber:  212223220120

import java.util.Scanner;

public class NestedTryExample {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int a = scanner.nextInt();
        int b = scanner.nextInt();
        try {
            try {
                if (b == 0) {
                    throw new ArithmeticException("Sorry! Number not divisible by zero");
                }
                int result = a / b;
                System.out.println("Result:" + result);
            } catch (ArithmeticException e) {
                System.out.println(e.getMessage());
                return;
            }
            
            try {
                String str = null;
                System.out.println(str.length());
            } catch (NullPointerException e) {
                System.out.println("NullPointerException");
            }
        } 
        finally {
            scanner.close();
        }
    }
}
*/
```

## OUTPUT:

![Screenshot 2025-05-10 061129](https://github.com/user-attachments/assets/7c5335f9-396c-4471-aca0-e1582e9ae382)


## RESULT:
Thus the Java Program To demonstrate the use of nested try-catch blocks and finally in Java exception handling executed successfully.

