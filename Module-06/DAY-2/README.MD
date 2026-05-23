# Ex.No:6(B) MULTI-LEVEL INHERITANCE

## AIM:
To demonstrate constructor chaining in multilevel inheritance in Java.

## ALGORITHM :

1. Start with class `A` having a constructor that prints a message.
2. Class `B` extends `A` and its constructor prints its own message.
3. Class `C` extends `B` and also prints its message in its constructor.
4. In the `main` method of class `A`, create an object of class `C`.
5. When the object is created, constructors are called in order: `A → B → C` due to inheritance.


## PROGRAM:
 ```
/*
Program to implement a MultiLevel Inheritance using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

public class A{
    public A(){
        System.out.println("Class A's display");
    }
    public static void main(String a[]){
        C obj = new C();
        
    }
}
class B extends A{
    public B(){
        System.out.println("Class B's display");
    }
}
class C extends B{
    public C(){
        System.out.println("Class C's display");
    }
}
*/
```

## OUTPUT:

![Screenshot 2025-05-10 055931](https://github.com/user-attachments/assets/21b9451a-5a83-4afc-a39b-c5076f22d551)


## RESULT:
Thus the java program To demonstrate constructor chaining in multilevel inheritance in Java executed successfully.





