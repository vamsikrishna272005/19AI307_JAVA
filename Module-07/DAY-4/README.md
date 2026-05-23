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
