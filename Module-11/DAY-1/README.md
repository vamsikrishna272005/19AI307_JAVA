# Ex.No:11(A)         JAVA TREESET
## AIM:
To read n strings into a TreeSet and display its elements in reverse (descending) order.


## ALGORITHM :

1. **Take input `n`** – the number of strings to be entered.
2. **Create a `TreeSet<String>`** to store and automatically sort the strings in ascending order.
3. **Read and add each string** to the TreeSet using a loop.
4. **Display the original TreeSet** to show elements in sorted order.
5. **Use `.descendingIterator()`** to iterate and print elements in reverse order.

## PROGRAM:
 ```
/*
Program to implement a JAVA TREESET using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

import java.util.*;
public class demo{
    public static void main(String args[]){
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        TreeSet<String> ts = new TreeSet<String>();
        for(int i =0; i<n;i++){
            ts.add(sc.next());
        }
        System.out.println("Original tree set:"+ts);
        Iterator it = ts.descendingIterator();
        System.out.println("Elements in Reverse Order:");
        while(it.hasNext()){
            System.out.println(it.next());
        }
    }
}
*/
```


## OUTPUT:

![Screenshot 2025-05-23 143825](https://github.com/user-attachments/assets/46c6ae38-ae80-43b7-bb36-1646971be315)


## RESULT:
Thus the java program To read n strings into a TreeSet and display its elements in reverse (descending) order executed successfully.

