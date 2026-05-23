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

 


