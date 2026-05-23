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







