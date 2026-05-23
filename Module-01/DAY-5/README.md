# Ex.No:1(E)  STATIC VARIABLE

## AIM:
Write a Java program to get the values of variables 'a' and 'b' respectively and check if atleast one of the conditions 'a < 50' or 'a < b' is true.

## ALGORITHM :
1. Start the program and create a Scanner object to take user input.

2. Read two integers a and b from the user.

3. Check the condition: if a is less than 50 or a is less than b.

4. If the condition is true, print "true", else print "false".

5. End the program.
## PROGRAM:
 ```
Program to implement a Static Variable using Java
Developed by: Vamsi Krishna G
RegisterNumber:  212223220120

import java.util.*;
public class Demo{
    public static void main(String args[]){
        int a,b;
        Scanner sc = new Scanner(System.in);
        a = sc.nextInt();
        b= sc.nextInt();
        if(a<50 || a<b){
            System.out.println("true");
        }
        else{
            System.out.println("false");
        }
        
    }
}
```


## OUTPUT:

![Screenshot 2025-05-09 112151](https://github.com/user-attachments/assets/634aa410-d9ac-4149-bf50-602e2f7f79eb)


## RESULT:
Thus, Java program to get the values of variables 'a' and 'b' respectively and check if atleast one of the conditions 'a < 50' or 'a < b' is true is executed successfully.

