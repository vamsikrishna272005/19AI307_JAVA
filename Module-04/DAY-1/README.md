# Ex.No:4(A)  JAVA CONSTRUCTOR
## AIM:
To demonstrate the usage of a static method for calculating power in Java.

## ALGORITHM :


1. Define a `Calculator` class with instance variables `num1` and `num2`.
2. Create a constructor to initialize `num1` and `num2`.
3. Define a static method `powerInt()` that calculates the power of `num1` raised to `num2` using `Math.pow()`.
4. In the `main()` method, create an instance of `Calculator` and pass values for `num1` and `num2`.
5. Call the static method `powerInt()` using the object and print the result.




## PROGRAM:
 ```
Program to implement a Constructor using Java
Developed by: Vamsi Krishna G
RegisterNumber:  212223220120

import java.lang.Math;

class Calculator {
    int num1, num2;

    public Calculator(int num1, int num2) {
        this.num1 = num1;
        this.num2 = num2;
    }

    public static int powerInt(int num1, int num2) {
        return (int) Math.pow(num1, num2);
    }
}

public class Sample {
    public static void main(String[] args) {
        Calculator obj = new Calculator(10, 2);
        System.out.println(obj.powerInt(10, 2));
    }
}

```

## OUTPUT:

![Screenshot 2025-05-09 140214](https://github.com/user-attachments/assets/503edd2f-b7bb-4919-82a5-0e0568302ac0)


## RESULT:
Thus the Java program To demonstrate the usage of a static method for calculating power in Java executed successfully.
