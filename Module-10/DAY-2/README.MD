# Ex.No:10(B) JAVA LINKED LIST
## AIM :
To read n strings into a LinkedList and find the last index of "Engineering" and "Programming".


## ALGORITHM :

1. **Take integer input `n`** – the number of strings to be added to the list.
2. **Create a `LinkedList<String>`** to store the input strings.
3. **Use a loop** to read `n` strings from the user and add them to the list.
4. **Print the entire list** to confirm the stored elements.
5. **Use `.lastIndexOf()`** to print the last index of `"Engineering"` and `"Programming"` in the list.


## PROGRAM:
 ```
/*
Program to implement a JAVA LINKED LIST using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

import java.util.*;
public class Demo{
    public static void main(String args[]){
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        LinkedList<String> ll = new LinkedList<String>();
        for(int i =0;i<n;i++){
            ll.add(sc.next());
        }
        System.out.println(ll);
        System.out.println("LastIndex for Engineering :"+ll.lastIndexOf("Engineering"));
        System.out.println("LastIndex for Programming :"+ll.lastIndexOf("Programming"));
    }
}
*/
```



## OUTPUT:

![Screenshot 2025-05-23 142621](https://github.com/user-attachments/assets/e6c9712f-f4b1-403b-a82f-088c4c203c35)


## RESULT:
Thus the Java program To read n strings into a LinkedList and find the last index of specific elements executed successfully.





