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




# Ex.No:7(C)             THREAD IN JAVA
## AIM:
To demonstrate how to create and manage a thread using Runnable, set thread name and priority, and display thread details.

## ALGORITHM :
1. Define a class `A` that implements `Runnable` and overrides the `run` method to print thread details.
2. In the `main` method, read a string input for the thread name using `Scanner`.
3. Create a new `Thread` object and assign it the `Runnable` object `a`.
4. Set the name of the thread using `setName` and its priority using `setPriority`.
5. Start the thread using `start()`, which invokes the `run` method and prints thread details.

## PROGRAM:
 ```
/*
Program to implement a Thread concepts using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

import java.util.*;

class A implements Runnable {
    public void run() {
        System.out.println("Priority of Thread: " + Thread.currentThread().getPriority());
        System.out.println("Name of Thread: " + Thread.currentThread().getName());
        System.out.println(Thread.currentThread());
    }
}

public class Demo {
    public static void main(String[] args) {
        A a = new A();
        Scanner sc = new Scanner(System.in);
        String name = sc.nextLine();

        Thread t = new Thread(a);
        t.setName(name);
        t.setPriority(2);
        t.start();
    }
}

*/
```


## OUTPUT:

![Screenshot 2025-05-10 061458](https://github.com/user-attachments/assets/c21a5273-0493-46c7-9117-10fa7c36ab09)


## RESULT:
Thus the Java program To demonstrate how to create and manage a thread using Runnable, set thread name and priority, and display thread details executed successfully.








# Ex.No:7(D) SYNCHRONIZATION
## AIM:
 To ensure thread safety and prevent race conditions when multiple threads access a critical section of code.
## ALGORITHM :
1. Define a static synchronized method `wish` that takes a name as input.
2. In the method, loop to print a welcome message and simulate delay using `Thread.sleep(400)`.
3. Ensure only one thread at a time can execute the method due to the `synchronized` keyword.
4. In a multi-threaded environment, use the method to demonstrate synchronization.
5. Prevent thread interference while printing the welcome message by using synchronization.

## PROGRAM:
 ```
/*
Program to implement a Packages using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

 class Display
{
    static synchronized void wish(String name){
        for(int i =0;i<=1;i++){
            System.out.print("Welcome :: ");
            try{
                Thread.sleep(400);
            }
            catch(InterruptedException e){
                
            }
            System.out.println(name);
        }
    }


}
*/
```

## OUTPUT:

![Screenshot 2025-05-10 061814](https://github.com/user-attachments/assets/ae466fc2-0809-425a-bfb8-ecb00ce97e9e)


## RESULT:
Thus the java program To ensure thread safety and prevent race conditions when multiple threads access a critical section of code executed successfully.

# Ex.No:7(E)  Thread Synchronization with Object Lock

## AIM:
To compute the square of numbers in a synchronized block, ensuring thread safety during execution.
## ALGORITHM :

1. Define a `square` method that calculates the square of numbers from 1 to `n`.
2. Use a synchronized block (`synchronized(this)`) to ensure that only one thread can execute the code block at a time.
3. Within the synchronized block, compute and print the square of each number.
4. Introduce a delay using `Thread.sleep(400)` to simulate time-consuming computation.
5. Handle any potential exceptions caused by the sleep method.



## PROGRAM:
 ```
/*
Program to implement a Method Overloading in Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

class Table
    {  
       void square(int n)
       {
           synchronized(this){
               for(int i = 1;i<=n;i++){
                   int j =i;
                   System.out.println("square for range value "+n+" "+i+":"+(j*j*j));
               }
               try{
                   Thread.sleep(400);
               }
               catch(Exception e){
                   System.out.println(e);
               }
           }
       }
             
    }
*/
```

## OUTPUT:

![Screenshot 2025-05-10 062004](https://github.com/user-attachments/assets/e03db657-a127-466b-8f8d-10cf9396a295)


## RESULT:

Thus the  java program To compute the square of numbers in a synchronized block, ensuring thread safety during execution executed successfully.


