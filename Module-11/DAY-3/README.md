# Ex.No:11(C)             JAVA LINKED HASHMAP
 ## AIM :

To insert entries into a LinkedHashMap, display them, replace the value of a specific key, and display the updated map.

## ALGORITHM :

1. **Take input `size`** – the number of key-value pairs to be inserted.
2. **Create a `LinkedHashMap<Integer, String>`** to maintain insertion order.
3. **Use a loop** to read keys and values and insert them into the map using `.put()`.
4. **Display the original map** using a `for-each` loop with `Map.Entry`.
5. **Replace the value** for key `100` using `.replace()` and print the updated map.


## PROGRAM:
 ```
/*
Program to implement a JAVA LINKED HASH MAP using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

import java.util.*;  
public class Mapp{  
 public static void main(String args[]){ 
     
  LinkedHashMap<Integer,String> map=new LinkedHashMap<>(); 
  Scanner sc=new Scanner(System.in);
  
  int size=sc.nextInt();
  for(int i=0;i<size;i++)
  {
  Integer a=sc.nextInt();
  String b=sc.next();
  map.put(a,b);  
  } 
 for(Map.Entry m: map.entrySet()){
     System.out.println(m.getKey()+" "+ m.getValue());
 }
 map.replace(100,"welcome to java");
 System.out.println("HashMap After Replace :");
 for(Map.Entry m: map.entrySet()){
     System.out.println(m.getKey()+" "+m.getValue());
 }
 
 }
}
*/
```

## OUTPUT:


![Screenshot 2025-05-23 144512](https://github.com/user-attachments/assets/aca788bf-830b-404b-a255-1db160d656df)

## RESULT:
Thus the  java program To insert entries into a LinkedHashMap, display them, replace the value of a specific key, and display the updated map executed successfully.








