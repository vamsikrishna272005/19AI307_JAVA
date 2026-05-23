# Ex.No:4(C)    CONSTRUCTOR CHAINING(SUPER KEYWORD)

## AIM:
To demonstrate method overriding and the use of the super keyword in Java.

## ALGORITHM :

1. Define an `Animal` class with a method `display()` that prints "I am an animal".
2. Define a `Dog` class that extends `Animal` and overrides the `display()` method to print "I am a dog".
3. In the `Dog` class, define a `print()` method that calls the `display()` method of the `Dog` class and the `display()` method of the `Animal` class using `super`.
4. In the `main()` method, create an instance of the `Dog` class and call the `print()` method.
5. The `print()` method will display both the overridden `display()` and the method from the superclass (`super.display()`), demonstrating method overriding and the `super` keyword.




## PROGRAM:
 ```
/*
Program to implement a Constructor Chaining using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

class Animal {
    void display(){
        System.out.println("I am an animal");
    }
}

class Dog extends Animal {
    void display(){
        System.out.println("I am a dog");
    }
    void print(){
        display();
        super.display();
    }
}

public class Main {
    public static void main(String[] args) {
        Dog myDog = new Dog();
        myDog.print();
    }
}
*/
```

## OUTPUT:

![Screenshot 2025-05-09 140741](https://github.com/user-attachments/assets/3c77bd21-0c5b-4d30-b6c4-9122917bb85b)


## RESULT:
Thus the java program To demonstrate method overriding and the use of the super keyword in Java executed successfully.




