# Ex.No:10(E)  JAVA LINKEDHASH SET

## AIM:
To read n strings into an ArrayList and print a sublist from index 1 to 2 using subList().
## ALGORITHM :


1. **Take input `n`** – the number of strings to read from the user.
2. **Create an `ArrayList<String>`** and populate it with user-entered strings.
3. **Print the original list** to confirm all input values.
4. **Use `.subList(1, 3)`** to extract a portion of the list (from index 1 to 2).
5. **Print the sublist** showing elements at index 1 and 2 of the original list.

## PROGRAM:
 ```
/*
Program to implement a LINKEDHASH SET
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

import java.util.*;
public class Demo{
    public static void main(String args[]){
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        ArrayList<String> al = new ArrayList<String>();
        for(int i =0;i<n;i++){
            al.add(sc.next());
        }
        System.out.println("Original list: "+al);
        List<String> newal = al.subList(1,3);
        System.out.println("Index of 1 to 3 elements print: "+newal);
        
    }
}
*/
```

## OUTPUT:

![Screenshot 2025-05-23 143524](https://github.com/user-attachments/assets/3f7bf245-b813-463b-8521-5f2e903e10dc)


## RESULT:

Thus the java program To read n strings into an ArrayList and print a sublist from index 1 to 2 using subList() executed successfully.
