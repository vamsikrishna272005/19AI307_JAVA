# Ex.No:10(D) JAVA HASHSET & LINKEDHASHSET

## AIM:
To read n strings from the user, store them in a HashSet, and display each unique string using an iterator.


## ALGORITHM :


1. **Take input `n`** – the number of strings to be entered.
2. **Create a `HashSet<String>`** to automatically store only unique strings.
3. **Use a loop** to read and add `n` strings from user input into the HashSet.
4. **Create an `Iterator<String>`** for the HashSet to traverse its elements.
5. **Print each unique string** using the iterator's `.next()` method in a loop.



## PROGRAM:
 ```
/*
Program to implement a JAVA HASHSET & LINKEDHASHSET using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

import java.util.*;

public class HashSetDemo{

public static void main(String args[]){

HashSet <String> hs = new HashSet <String>();
Scanner sc=new Scanner(System.in);
int n=sc.nextInt();
for(int i=0;i<n;i++)
{
    
hs.add(sc.next());

}
 Iterator<String> i=hs.iterator();  
 while(i.hasNext())  
 {  
    System.out.println(i.next());  
 }  

}
}
*/
```



## OUTPUT:

![Screenshot 2025-05-23 143306](https://github.com/user-attachments/assets/1c67db74-7aa8-40cc-9507-d87ce0d7885a)


## RESULT:
Thus the java program To read n strings from the user, store them in a HashSet, and display each unique string using an iterator executed successfully.



