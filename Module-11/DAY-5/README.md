# Ex.No:11(E)  JAVA HASHMAP

## AIM:
To read strings into a TreeSet, and print the first and last elements in sorted order.
## ALGORITHM :

1. **Take input `n`** – number of strings to be added.
2. **Create a `TreeSet<String>`** to store strings in natural (sorted) order.
3. **Read and add each string** to the TreeSet using a loop.
4. **Display the complete TreeSet** using `System.out.println()`.
5. **Retrieve and print** the first and last elements using `.first()` and `.last()` methods.


## PROGRAM:
 ```
/*
Program to implement a HASHMAP
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

import java.util.*;
public class Demo{
    public static void main(String args[]){
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        TreeSet<String> t1 = new TreeSet<String>();
        for(int i =0;i<n;i++){
            t1.add(sc.next());
        }
        System.out.println("Tree set:");
        System.out.println(t1);
        Object first = t1.first();
        Object second = t1.last();
        System.out.println("First Element is: "+ first);
        System.out.println("Last Element is: "+ second);
    }
}
*/
```

## OUTPUT:


![Screenshot 2025-05-23 145121](https://github.com/user-attachments/assets/cad638f6-c049-4bed-909e-a85904b3d4d1)

## RESULT:
Thus the java program To read strings into a TreeSet, and print the first and last elements in sorted order executed successfully.




