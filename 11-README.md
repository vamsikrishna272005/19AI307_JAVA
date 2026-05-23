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









# Ex.No:11(D) RELATED TO MAP CONCEPTS

## AIM:
To read key-value pairs from the user, store them in a HashMap, and display all entries.

## ALGORITHM :


1. **Take input `n`** – number of key-value pairs to be inserted.
2. **Create a `HashMap<Integer, String>`** to store integer keys and string values.
3. **Use a loop** to read `n` integer-string pairs from the user and insert them using `.put()`.
4. **Iterate over the map** using a `for-each` loop with `Map.Entry`.
5. **Print each key-value pair** using `getKey()` and `getValue()`.


## PROGRAM:
 ```
/*
Program to implement a RELATED TO MAP CONCEPTS using Java
Developed by: Vamsi krishna G
RegisterNumber: 212223220120

import java.util.*;
public class Demo{
    public static void main(String args[]){
        Scanner sc = new Scanner(System.in);
        Map<Integer,String> map = new HashMap<Integer,String>();
        int n = sc.nextInt();
        for(int i =0;i<n;i++){
            Integer a = sc.nextInt();
            String b = sc.next();
            map.put(a,b);
        }
        for(Map.Entry m: map.entrySet()){
            System.out.println(m.getKey()+" "+ m.getValue());
        }
    }
}
*/
```





## OUTPUT:

![Screenshot 2025-05-23 144849](https://github.com/user-attachments/assets/ce225056-85b6-4904-9c23-fb0037d15e50)


## RESULT:
Thus the java program To read key-value pairs from the user, store them in a HashMap, and display all entries executed successfully.



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




