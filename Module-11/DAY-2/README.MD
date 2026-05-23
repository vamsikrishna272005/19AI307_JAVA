# Ex.No:11(B)   JAVA MAP & HASHMAP AND HASHTABLE
## AIM :
To insert key-value pairs into a HashMap, display all entries, and retrieve the value for a specific key.

## ALGORITHM :


1. **Take input `size`** – the number of key-value pairs to be stored.
2. **Create a `HashMap<Integer, String>`** to map integer keys to string values.
3. **Use a loop** to read keys and values from the user and insert them into the map using `.put()`.
4. **Iterate through the map** using `Map.Entry` to print all key-value pairs.
5. **Retrieve a value** using `.get(100)` and print the result for key `100`.



## PROGRAM:
 ```
/*
Program to implement a JAVA MAP & HASHMAP AND HASHTABLE using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

import java.util.*;  
public class Mapp{  
 public static void main(String args[]){ 
     
  HashMap<Integer,String> map=new HashMap<Integer,String>(); 
  Scanner sc=new Scanner(System.in);
  
  int size=sc.nextInt();
  for(int i=0;i<size;i++)
  {
  Integer a=sc.nextInt();
  String b=sc.next();
  map.put(a,b);  
  } 
 
  for(Map.Entry m:map.entrySet()){  
   System.out.println(m.getKey()+" "+m.getValue());  
  }
  Integer key = 100; String value = map.get(key);


  System.out.println("value: "+ value);


 }  
}  
*/
```



## OUTPUT:

![Screenshot 2025-05-23 144219](https://github.com/user-attachments/assets/e4f58d5f-875f-4d6c-8e04-f56c54ae4d7c)


## RESULT:
Thus the java program To insert key-value pairs into a HashMap, display all entries, and retrieve the value for a specific key executed successfully.







