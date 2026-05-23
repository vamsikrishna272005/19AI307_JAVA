# Ex.No:3(A)  STRING AND ITS OPERATIONS IN JAVA
## AIM:
To compare three input strings using case-insensitive comparison in Java.

## ALGORITHM :
1. Initialize Scanner and read three strings from user input.
2. Store the input strings in `str1`, `str2`, and `str3`.
3. Compare `str1` and `str2` using `equalsIgnoreCase()` and print the result.
4. Compare `str1` and `str3` using `equalsIgnoreCase()` and print the result.
5. Compare `str2` and `str3` using `equalsIgnoreCase()` and print the result.

## PROGRAM:
 ```
Program to implement a String and its Operations using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

import java.util.*;
public class Demo{
    public static void main(String args[]){
        Scanner sc = new Scanner(System.in);
        String str1 = sc.nextLine();
        String str2 = sc.nextLine();
        String str3 = sc.nextLine();
        
        System.out.println(str1.equalsIgnoreCase(str2));
        System.out.println(str1.equalsIgnoreCase(str3));
        System.out.println(str2.equalsIgnoreCase(str3));
        
    }
}

```

## OUTPUT:


![Screenshot 2025-05-09 134816](https://github.com/user-attachments/assets/780c6667-35b3-404d-acd5-5599fe6544d8)

## RESULT:
Thus the java Program to compare three input strings using case-insensitive comparison in Java executed successfully.

