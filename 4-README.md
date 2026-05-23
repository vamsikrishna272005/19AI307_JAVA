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

# Ex.No:4(B) INTRODUCTION TO JAVA INHERITANCE

## AIM:
To demonstrate inheritance, data input, grade calculation, and display in Java.

## ALGORITHM :

1. Define a `Student` class with instance variables `name`, `classn`, and `roll_no`, and a method `getData()` to take input for these variables.
2. Create a `Grade` class that extends `Student`, adding `tmarks`, `per`, and a method `calGrade()` to calculate the percentage.
3. Define a method `display()` in the `Grade` class to print the student's details along with the calculated percentage.
4. In the `main()` method, create an instance of `Grade`, call `getData()` to input student information, calculate the grade using `calGrade()`, and display the results with `display()`.
5. Use `System.out.printf()` to format and display the percentage with one decimal place.

## PROGRAM:
 ```
/*
Program to implement a Inheritance using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

import java.util.Scanner;

class Student {
    String name;
    String classn; 
    int roll_no;

    void getData() {
        Scanner sc = new Scanner(System.in);
        name = sc.nextLine();
        
        classn = sc.nextLine();
       
        roll_no = sc.nextInt();
    }
}

public class Grade extends Student {
    float tmarks = 98.5f; 
    float per;

    void calGrade() {
        per = (tmarks / 500) * 100; 
    }

    void display() {
        System.out.println("Roll Number is: " + roll_no);
        System.out.println("Your name is: " + name);
        System.out.println("Your class is: " + classn);
         System.out.printf("Your percentage is: %.1f\n", per);
    }

    public static void main(String args[]) {
      
        Grade obj = new Grade();
        obj.getData();
        obj.calGrade();
        obj.display();
        
    }
}

*/
```
## OUTPUT:

![Screenshot 2025-05-09 140442](https://github.com/user-attachments/assets/97c29900-343a-4ff3-88b4-3ceb7f8175c4)


## RESULT:
Thus the Java program to implement the inheritance concept for employee details was  executed successfully.


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





# Ex.No:4(D) FINAL & STATIC IN JAVA

## AIM:
 To create a company class using a constructor and display its details including a final ID.
## ALGORITHM :

1. Define a `Company` class with instance variables `name` and `add`, and a `final` variable `id` initialized to a constant value.
2. Create a constructor that accepts two parameters to initialize `name` and `add`.
3. Define a `print()` method to display the company ID, name, and address.
4. In the `main()` method, create an object of `Company` and pass values to the constructor.
5. Call the `print()` method to display the complete details of the company.


## PROGRAM:
 ```
/*
Program to implement a final & Static using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

class Company{
    String name,add;
    final String  id = "ED12G45";
    Company(String n , String a){
       name = n;
       add = a;
    }
    void print(){
        System.out.println("Company Details are,");
        System.out.println("Id is "+ id );
        System.out.println("Name is "+name);
        System.out.println("Address is "+add);
    }
}
public class Demo{
    public static void main(String ar[]){
        Company obj = new Company("ABC Foods","Chennai");
        obj.print();
    }
}
*/
```

## OUTPUT:

![Screenshot 2025-05-09 142955](https://github.com/user-attachments/assets/9f41f702-9269-47f2-9527-4f5a5a977f5a)


## RESULT:
Thus, the java program to create a company class using a constructor and display its details including a final ID.

# Ex.No:4(E)  Character Input Using do-while
## AIM:
To read and display multiple lines of character input using a do-while loop in Java.
## ALGORITHM :

1. Initialize `Scanner` and prompt the user to enter the number of characters (lines) to input.
2. Declare a `String` array of size `a + 1` to store the input lines.
3. Use a `do-while` loop to read lines from the user using `nextLine()` and store them in the array.
4. Print each input line immediately after reading it.
5. Continue the loop until `i <= a` to collect all the required inputs including handling the initial newline after `nextInt()`.

## PROGRAM:
 ```
/*
Program to implement a Parameterized Constructor Using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

import java.util.*;
public class Demo{
    public static void main(String ar[]){
        Scanner sc = new Scanner(System.in);
        System.out.print("Entered characters are:");
        int a = sc.nextInt();
        String[] arr = new String[a+1];
        int i =0;
        do{
            arr[i] = sc.nextLine();
            System.out.println(arr[i]);
            i++;
        }while(i<=a);
      
    }
}
*/
```

## OUTPUT:

![Screenshot 2025-05-09 143820](https://github.com/user-attachments/assets/3d42992b-116c-41c3-902f-36c49ee6b28b)


## RESULT:
Thus, the  java program To read and display multiple lines of character input using a do-while loop in Java executed successfully.

 


