# Ex.No:6(A)  INNER CLASS
## AIM:
To demonstrate accessing outer class members using a non-static inner class in Java.

## ALGORITHM :

1. Define an outer class `Employee` with private attributes `Emp_Id` and `Emp_Name`.
2. Create a non-static inner class `Salary` that contains salary-related fields.
3. Implement a `display` method in the inner class to print employee details and total salary.
4. In the `main` method, create an instance of the outer class `Employee`.
5. Use the outer class instance to create the inner class object and call the `display` method.

## PROGRAM:
 ```
/*
Program to implement a Inner Class using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

class Employee {
    private String Emp_Id = "EMP123";
    private String Emp_Name = "John";

    class Salary {
        private float Basic = 22500;
        private float Allowance = 2300;

        public void display() {
            System.out.println(Emp_Id + " " + Emp_Name  + " "+(Basic + Allowance));
        }
    }
}

public class Main {
    public static void main(String[] args) {
        Employee emp = new Employee();
        Employee.Salary obj = emp.new Salary();
        obj.display();
    }
}

*/
```

## OUTPUT:

![Screenshot 2025-05-10 055702](https://github.com/user-attachments/assets/84ecf805-8801-4829-b0c3-de887fe88f39)


## RESULT:
Thus, the Java Program To demonstrate accessing outer class members using a non-static inner class in Java executed successfully.


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







# Ex.No:6(D) PACKAGES
## AIM:
 To demonstrate how to define and use a class inside a Java package.
 
## ALGORITHM :

1. Declare the package name using `package JavaProgramming.arrays;` at the top of the file.
2. Define the `TwoPointers` class as `public` so it can be accessed outside the package.
3. Inside `main`, print a simple message to verify successful compilation and execution.
4. Save the file as `TwoPointers.java` inside the correct folder structure: `JavaProgramming/arrays/`.
5. Compile using `javac JavaProgramming/arrays/TwoPointers.java` and run using `java JavaProgramming.arrays.TwoPointers`.

## PROGRAM:
 ```
/*
Program to implement a Packages using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

package JavaProgramming.arrays;

public class TwoPointers {

    public static void main(String[] args) {
        System.out.println("Inside the package");
    }
}
*/
```

## OUTPUT:

![Screenshot 2025-05-10 060505](https://github.com/user-attachments/assets/fe54032b-0a13-452a-99b1-c61158e36091)


## RESULT:
Thus, To demonstrate how to define and use a class inside a Java package executed successfully.


# Ex.No:6(E) Arrays and Looping

## AIM:
To find and display the smallest number in a user-defined array.

## ALGORITHM :

1. Read the size of the array from the user.
2. Create an integer array of the specified size.
3. Read elements into the array using a loop.
4. Initialize a variable with the first element and compare it with the rest to find the smallest.
5. Print the smallest number after the loop ends.

## PROGRAM:
 ```
/*
Program to implement a Multiple Inheritance
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

import java.util.*;
public class Demo{
    public static void main(String ar[]){
        int a;
        Scanner sc = new Scanner(System.in);
        a = sc.nextInt();
        int[] arr = new int[a];
        for(int i =0;i<a;i++){
            arr[i] = sc.nextInt();
        }
        int lar = arr[0];
        for(int i =0;i<a;i++){
            if(lar> arr[i]){
                lar = arr[i];
            }
        }
        System.out.println("Smallest Number = "+lar);
    }
}
*/
```
## OUTPUT:

![Screenshot 2025-05-10 060806](https://github.com/user-attachments/assets/d67426d4-de06-467b-9d38-971dd45e6d06)


## RESULT:

Thus, the java program To find and display the smallest number in a user-defined array executed successfully.
