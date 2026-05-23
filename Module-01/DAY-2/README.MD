# Ex.No:1(B) VARIABLES AND OPERATOR

## AIM:
To display the number of days in a month based on its numeric input (1–12) using basic conditional statements.

## ALGORITHM :
1. Start the program and create a Scanner object to read input from the user.

2. Read two integers a and b from the user.

3. Check if a is less than 50.

4. If a is less than 50 and also less than b, set t to true and print it.

5. If a is not less than 50, set t to false and print it.
## PROGRAM:
 ```
Program to implement a variable and operators using Java
Developed by: Vamsi Krishna G
RegisterNumber:  212223220120

import java.util.*;
public class Demo{
    public static void main(String args[]){
        Scanner sc = new Scanner(System.in);
        int a , b;
        boolean t;
        a = sc.nextInt();
        b = sc.nextInt();
        if(a<50){
            if(a<b){
                t = true;
                System.out.println(t);
            }
        }
        else{
                t= false;
                System.out.println(t);
            }
    }
}


```

## OUTPUT:

![Screenshot 2025-05-09 132153](https://github.com/user-attachments/assets/4a52f1e8-c401-449a-ac01-e420fdb279c2)


## RESULT:
Thus, to display the number of days in a month based on its numeric input (1–12) using basic conditional statements is executed successfully.

