# Ex.No:3(C)    STRING BUILDER IN JAVA

## AIM:
To Create a java program to convert string into a character array and display it in a specific format.
## ALGORITHM :

1. Initialize `Scanner` and read a string input from the user.
2. Convert the string to a character array using `toCharArray()`.
3. Determine the length of the character array.
4. Loop through the array, printing each character with a comma separator.
5. Display the character array in the format `[char1, char2, ..., charN]`.

## PROGRAM:
 ```
Program to implement a String Builder using Java
Developed by: Vamsi Krishna G
RegisterNumber:  212223220120

import java.util.*;
public class Demo{
    public static void main(String args[]){
        Scanner sc = new Scanner(System.in);
        String str1 = sc.nextLine();
        char[] arr = str1.toCharArray();
        int n = arr.length;
        System.out.print("[");
        for(int i =0;i<n;i++){
            System.out.print(arr[i]);
            if (i < n - 1) {
                System.out.print(", ");
            }
        }
        System.out.print("]");
    }
}
```


## OUTPUT:

![Screenshot 2025-05-09 135323](https://github.com/user-attachments/assets/fbe70b98-607c-43dd-8a93-3a0fac08e7dd)


## RESULT:
Thus the java program to convert string into a character array and display it in a specific format executed successfully.



