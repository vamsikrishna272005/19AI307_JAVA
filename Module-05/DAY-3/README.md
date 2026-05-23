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






