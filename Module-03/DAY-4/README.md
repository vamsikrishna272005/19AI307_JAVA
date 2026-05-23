# Ex.No:3(D) STRING TOKENIZER IN JAVA

## AIM:
To tokenize a string using multiple delimiters and display each token in Java.

## ALGORITHM :

1. Initialize `Scanner` and read a string input from the user.
2. Create a `StringTokenizer` object with the input string and delimiters `://.`.
3. Check if there are more tokens available using `hasMoreTokens()`.
4. Use `nextToken()` to retrieve and display each token one by one.
5. Continue the process until all tokens are displayed.


## PROGRAM:
 ```

Program to implement a String Tokenizer using Java
Developed by: Vamsi Krishna G
RegisterNumber:  212223220120

import java.util.*;

public class Demo{
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String str= sc.nextLine();
        StringTokenizer t= new StringTokenizer(str, "://.", true);

        while (t.hasMoreTokens()) {
            System.out.println(t.nextToken());
        }
    }
}

```

## OUTPUT:
![Screenshot 2025-05-09 135612](https://github.com/user-attachments/assets/ce8dd089-1161-4cd5-b8b8-ac07ebf3c661)



## RESULT:
Thus the java program To tokenize a string using multiple delimiters and display each token in Java executed successfully.
