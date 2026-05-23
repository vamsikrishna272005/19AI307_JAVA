# Ex.No:5(A)  DATA HIDING AND ENCAPSULATION
## AIM:
To perform addition of two numbers using setter methods and encapsulation in Java.

## ALGORITHM :

1. Define an `Addition` class with two private integer variables `num1` and `num2`.
2. Create a `set()` method to assign values to `num1` and `num2` using the `this` keyword.
3. Define an `add()` method that returns the sum of `num1` and `num2`.
4. In the `main()` method, use `Scanner` to read two integers from the user.
5. Create an `Addition` object, set the values using `set()`, call `add()`, and print the result.


## PROGRAM:
 ```
/*
Program to implement a Data Hiding & Encapsulation using Java
Developed by: Vamsi Krishna G
RegisterNumber:  212223220120

import java.util.*;
class Addition{
    private int num1 , num2;
    
    public int add(){
        return num1+num2;
    }
    public void set(int num1, int num2){
        this.num1 = num1 ;
        this.num2 = num2;
    }
}
public class Demo{
    public static void main(String a[]){
        Scanner sc = new Scanner(System.in);
        int num1, num2;
        num1 = sc.nextInt();
        num2 = sc.nextInt();
        Addition obj = new Addition();
        obj.set(num1,num2);
        int res = obj.add();
        System.out.println(res);
    }
}
*/
```

## OUTPUT:

![Screenshot 2025-05-09 144034](https://github.com/user-attachments/assets/166a0c8c-6658-4450-80f0-4c3d0c783723)


## RESULT:
Thus , the  java program to perform addition of two numbers using setter methods and encapsulation in Java.
