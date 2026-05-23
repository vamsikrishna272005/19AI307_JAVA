# Ex.No:5(D) IS-A RELATIONSHIP AND HAS-A RELATIONSHIP
## AIM:
To reverse a given number using object-oriented programming in Java.
 
## ALGORITHM :

1. Begin by accepting an integer input from the user using `Scanner`.
2. Define a class `NumberReverser` with a private integer data member and a constructor to initialize it.
3. Implement a `reverse` method that calculates the reverse of the number using a loop.
4. In the `main` method, create an instance of `NumberReverser` with user input.
5. Call the `reverse` method and print the reversed number.
## PROGRAM:
 ```
/*
Program to implement a IS-A RELATIONSHIP AND HAS-A RELATIONSHIP using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

import java.util.*;

class NumberReverser {
    private int number;

    public NumberReverser(int number) {
        this.number = number;
    }

    public int reverse() {
        int rev = 0, num = number;
        while (num > 0) {
            rev = rev * 10 + num % 10;
            num /= 10;
        }
        return rev;
    }
}

public class Demo {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int num = sc.nextInt();
        
        NumberReverser reverser = new NumberReverser(num);
        System.out.println("The reverse of the given number is: " + reverser.reverse());
        
        sc.close();
    }
}

*/
```
## OUTPUT:
![Screenshot 2025-05-10 055249](https://github.com/user-attachments/assets/386c82d7-ffd0-443f-ba90-c37ad9b1a2dc)


## RESULT:
Thus the java program To reverse a given number using object-oriented programming in Java executed successfully.
