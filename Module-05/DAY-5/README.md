# Ex.No:5(E) Class and Object
## AIM:
To add two numbers using a class with methods for setting values and displaying the result.
## ALGORITHM :

1. Start by reading two integers from the user using `Scanner`.
2. Define a class `A` with two integer data members.
3. Implement the `setnum` method to assign values to `num1` and `num2` using `this` keyword.
4. Create a `display` method to print the sum of `num1` and `num2`.
5. In the `main` method, create an object of class `A`, call `setnum`, and then `display`.

## PROGRAM:
 ```
/*
Program to implement a HAS-A RelationShip
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

import java.util.*;
class A{
    int num1, num2;
    public void setnum(int num1, int num2){
        this.num1 = num1 ; 
        this.num2 = num2;
    }
    public void display(){
        System.out.println(num1+num2);
    }
}
public class Demo{
    public static void main(String a[]){
        int num1, num2;
        Scanner sc = new Scanner(System.in);
        num1 = sc.nextInt();
        num2 = sc.nextInt();
        A obj = new A();
        obj.setnum(num1, num2);
        obj.display();
    }
}
*/
```

## OUTPUT:

![Screenshot 2025-05-10 055459](https://github.com/user-attachments/assets/5e1ca58f-e94f-490d-babf-6d02aaff0d43)


## RESULT:
Thus the java program To add two numbers using a class with methods for setting values and displaying the result executed successfully.

