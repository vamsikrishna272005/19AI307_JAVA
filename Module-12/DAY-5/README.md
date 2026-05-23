# Ex.No:12(E) Replace Substring Using StringBuilder

## AIM:
To replace characters in a string between specified indices using StringBuilder.replace() method.
## ALGORITHM :

1. **Take input string** from the user.
2. **Create a `StringBuilder` object** initialized with the input string.
3. **Use `replace(start, end, newString)`** to replace characters from index 1 to 2 (end index exclusive) with `"Java"`.
4. **Print the modified string** by calling `toString()` implicitly via `System.out.println()`.
5. **Observe the changed string reflecting the replacement.**


## PROGRAM:
 ```
/*
Program to implement a JAVA DEQUEUE
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

import java.util.*;
public class Demo{
    public static void main(String args[]){
        Scanner sc= new Scanner(System.in);
        String str = sc.nextLine();
        StringBuilder sb = new StringBuilder(str);
        sb.replace(1,3,"Java");
        System.out.println(sb);
    }
}
*/
```


## OUTPUT:

![Screenshot 2025-05-23 150320](https://github.com/user-attachments/assets/3feb7599-bf9c-4cf6-b3a4-ddb17e7f40a7)


## RESULT:

Thus the java program To replace characters in a string between specified indices using StringBuilder.replace() method executed successfully.


