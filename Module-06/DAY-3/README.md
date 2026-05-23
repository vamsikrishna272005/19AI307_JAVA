# Ex.No:6(C)             HIERARCHICAL INHERITANCE 

## AIM:
  To perform addition and subtraction using inheritance with shared data members

## ALGORITHM :

1. Create a base class `Number` with two numbers and a result variable.
2. Derive class `Addition` from `Number` and override `display` to compute and print the sum.
3. Derive class `Subraction` from `Number` and override `display` to compute and print the difference.
4. In the `main` method, create objects of `Addition` and `Subraction`.
5. Call their `display` methods to show the results of both operations.

## PROGRAM:
 ```
/*
Program to implement a Hierarchical Inheritance using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

class Number{
    int num1 = 10;
    int num2 = 5;
    int res;
}
class Addition extends Number{
    void display(){
    res = num1 + num2;
    System.out.println("Addition of 2 values "+res);
    }
}
class Subraction extends Number{
    void display(){
    res = num1 - num2;
    System.out.println("Subtraction of 2 values "+res);
    }
}
public class Demo{
    public static void main(String a[]){
        Addition obj = new Addition();
        obj.display();
        Subraction obj1 = new Subraction();
        obj1.display();
    }

}
*/
```

## OUTPUT:
![Screenshot 2025-05-10 060148](https://github.com/user-attachments/assets/d4763aa6-8330-49c2-9f9d-156cb965914a)


## RESULT:
Thus the java program To perform addition and subtraction using inheritance with shared data members executed successfully.






