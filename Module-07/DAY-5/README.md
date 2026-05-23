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


