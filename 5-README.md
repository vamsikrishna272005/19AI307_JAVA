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

# Ex.No:5(B) TIGHTLY ENCAPSULATED CLASS

## AIM:
To Create a java program to reverse a given string using StringBuilder in Java.

## ALGORITHM :

1. Define a `Reverse` class with a string variable `str1` and a method `set()` to assign its value.
2. In the `display()` method, create a `StringBuilder` object with `str1` and reverse it using `reverse()`.
3. Print the reversed string to the console.
4. In the `main()` method, use `Scanner` to take a string input from the user.
5. Create an object of the `Reverse` class, pass the input to `set()`, and call `display()` to print the reversed string.




## PROGRAM:
 ```
/*
Program to implement a tightly encapsulated class using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

import java.util.*;
class Reverse{
    String str1;
    public void set(String str1){
        this.str1= str1;
    }
    public void display(){
        StringBuilder sb = new StringBuilder(str1);
        System.out.println(sb.reverse());
    }
}
public class Demo{
    public static void main(String a[]){
        Scanner sc = new Scanner(System.in);
        String str = sc.nextLine();
        Reverse obj = new Reverse();
        obj.set(str);
        obj.display();
    }
}
*/
```


## OUTPUT:

![Screenshot 2025-05-09 144317](https://github.com/user-attachments/assets/fd1b3d5d-d42a-4057-86a3-89627b710e19)


## RESULT:
Thus a java program to reverse a given string using StringBuilder in Java executed successfully.




# Ex.No:5(C)    GETTER AND SETTER METHOD

## AIM:
To input a string and display its first and last character using a class-based structure.

## ALGORITHM :

1. Start the program and import the Scanner class for user input.
2. Define a class `Display` with private string data and methods to set, get, and display string characters.
3. In the `main` method, read a string input from the user using `Scanner`.
4. Create an object of the `Display` class and pass the input string using the `set` method.
5. Call the `display` method to print the first and last character of the string.


## PROGRAM:
 ```
/*
Program to implement a Getter and Setter using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

import java.util.*;
class Display{
    private String str;
    public void set(String str){
        this.str= str;
    }
    public String get(){
        return str;
    }
    public void display(){
        System.out.println(str.charAt(0));
        System.out.println(str.charAt(str.length()-1));
    }
}
public class Demo{
    public static void main(String a[]){
        String str ; 
        Scanner sc= new Scanner(System.in);
        str = sc.nextLine();
        Display obj = new Display();
        obj.set(str);
        obj.display();
    }
}
*/
```

## OUTPUT:
![Screenshot 2025-05-10 054918](https://github.com/user-attachments/assets/791354b1-5406-40e2-a82a-35309e89b9da)



## RESULT:
Thus the java program to input a string and display its first and last character using a class-based structure executed successfully.







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

