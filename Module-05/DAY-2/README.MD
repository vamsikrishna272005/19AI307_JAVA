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



