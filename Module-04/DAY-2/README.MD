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

