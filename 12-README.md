# Ex.No:12(A)         JAVA TREE MAP
## AIM:
To create two TreeMap objects, populate them with key-value pairs, and merge the second into the first using putAll().

## ALGORITHM :


1. **Take input `n`** – number of key-value pairs for the first TreeMap (`t1`).
2. **Create and populate `TreeMap<String, String> t1`** using user input.
3. **Take input `n1`** – number of entries for the second TreeMap (`t2`).
4. **Create and populate `TreeMap<String, String> t2`** similarly with key-value pairs.
5. **Use `t1.putAll(t2)`** to merge `t2` into `t1` and display the updated `t1`.

## PROGRAM:
 ```
/*
Program to implement a JAVA TREE MAP using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

import java.util.*;
public class Demo{
    public static void main(String args[]){
       TreeMap<String,String> t1 = new TreeMap<String, String>();
       Scanner sc= new Scanner(System.in);
       int n = sc.nextInt();
       for(int i =0;i<n;i++){
           String str1 = sc.next();
           String str2 = sc.next();
           t1.put(str1,str2);
       }
       System.out.println("Tree Map 1: "+ t1);
       int n1 = sc.nextInt();
       TreeMap<String,String> t2 = new TreeMap<String,String>();
       for(int i =0;i<n1;i++){
           String str3 = sc.next();
           String str4 = sc.next();
           t2.put(str3,str4);
       }
       System.out.println("Tree Map 2: "+ t2);
       t1.putAll(t2);
       System.out.println("After coping map2 to map1: "+ t1);
    }
}
*/
```

## OUTPUT:

![Screenshot 2025-05-23 145352](https://github.com/user-attachments/assets/51d1ca78-7ac4-4384-a496-d81037d5090a)


## RESULT:
Thus the Java program To create two TreeMap objects, populate them with key-value pairs, and merge the second into the first using putAll() executed successfully.

# Ex.No:12(B)   COMPARABLE & COMPARATOR INTERFACE
## AIM :
To create and sort a list of Student objects based on the name field using a custom comparator.


## ALGORITHM :


1. **Create a `Student` class** with fields `rollno`, `name`, and `address`, and override `toString()` for display.
2. **Implement a `Comparator<Student>`** named `Sortbyname` to compare students based on their names.
3. **Take input `size`** – number of students to be added, then use a loop to create and store student objects in an `ArrayList`.
4. **Print the unsorted list** using a loop.
5. **Sort the list using `Collections.sort()`** with the `Sortbyname` comparator, then print the sorted list.

## PROGRAM:
 ```
/*
Program to implement a COMPARABLE & COMPARATOR INTERFACE using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

import java.io.*;
import java.lang.*;
import java.util.*;
class Student {
 
    int rollno;
    String name, address;
    public Student(int rollno, String name, String address)
    {
        this.rollno = rollno;
        this.name = name;
        this.address = address;
    }
    public String toString()
    {
         return this.rollno + " " + this.name + " "
            + this.address;
    }
}
class Sortbyname implements Comparator<Student> {
 
    public int compare(Student a, Student b)
    {
 
        return a.name.compareTo(b.name);
    }
}
public class Main {
    public static void main(String[] args)
    {
        ArrayList<Student> ar = new ArrayList<Student>();
        Scanner sc=new Scanner(System.in);
        int size=sc.nextInt();
        for(int i=0;i<size;i++)
        {
        ar.add(new Student(sc.nextInt(),sc.next(),sc.next()));
        }
      
        System.out.println("Unsorted");
 
        
        for (int i = 0; i < ar.size(); i++)
            System.out.println(ar.get(i));
 
         Collections.sort(ar, new Sortbyname());
 
        
        System.out.println("\nSorted by name");
 
        
        for (int i = 0; i < ar.size(); i++)
            System.out.println(ar.get(i));
 
       
    }
}
*/
```


## OUTPUT:
![Screenshot 2025-05-23 145552](https://github.com/user-attachments/assets/df287203-5c31-41f9-95d2-4dd03a0aee29)




## RESULT:
Thus the java program To create and sort a list of Student objects based on the name field using a custom comparator executed successfully.





# Ex.No:12(C)             JAVA STACK & VECTOR
 ## AIM :

To add pairs of strings into a Vector, display the vector, and print the first element.
## ALGORITHM :

1. **Create a `Vector<String>`** to store string elements.
2. **Take input `size`** – the number of pairs of strings to be entered.
3. **Use a loop** to input and add two strings per iteration into the vector using `.add()`.
4. **Display the complete vector** using `System.out.println()`.
5. **Retrieve and print the first element** using `.firstElement()`.

## PROGRAM:
 ```
/*
Program to implement a JAVA STACK & VECTOR  using Java
Developed by: Vamsi Krishna G
RegisterNumber:  212223220120

import java.util.*;

public class VectorDemo {
	public static void main(String args[])
	{

		
		Vector<String> vec_tor = new Vector<String>();
        Scanner sc=new Scanner(System.in);
        int size=sc.nextInt();
	    for(int i=0;i<size;i++)
	    {
		vec_tor.add(sc.next());
	    vec_tor.add(sc.next());
	    }
	

		System.out.println("The vector is: " + vec_tor);

	    System.out.println("The first element is: "
                           + vec_tor.firstElement());
	}
}

*/
```


## OUTPUT:

![Screenshot 2025-05-23 145825](https://github.com/user-attachments/assets/3a69854a-c691-44f3-bd95-2e8ee9689f3d)


## RESULT:

Thus the java program To add pairs of strings into a Vector, display the vector, and print the first element executed successfully.









# Ex.No:12(D) JAVA QUEUE
## AIM:
To add integers into a PriorityQueue and iterate over the elements using an iterator.

## ALGORITHM :


1. **Create a `PriorityQueue<Integer>`** to hold integer elements with natural ordering.
2. **Take input `size`** – the number of integers to add.
3. **Use a loop** to read integers from the user and add them to the priority queue.
4. **Create an iterator** for the priority queue using `.iterator()`.
5. **Iterate and print all elements** using the iterator’s `hasNext()` and `next()` methods.


## PROGRAM:
 ```
/*
Program to implement a JAVA QUEUE using Java
Developed by: Vamsi krishna G
RegisterNumber: 212223220120

import java.util.*;

public class PriorityQueueDemo {
	

	public static void main(String args[])
	{
	
		PriorityQueue<Integer> pQueue = new PriorityQueue<Integer>();
        
	    Scanner sc=new Scanner(System.in);
	    int size=sc.nextInt();
	    for(int i=0;i<size;i++){
	        pQueue.add(sc.nextInt());
	    }
	   Iterator iterator = pQueue.iterator();
	   System.out.println("Iterate the elements from the queue using while loop:");
  
        while (iterator.hasNext()) {
            System.out.print(iterator.next() + " ");
        }
		
	}
}

*/
```



## OUTPUT:

![Screenshot 2025-05-23 150024](https://github.com/user-attachments/assets/d12761cf-4682-42e1-ae86-72e841565e4e)


## RESULT:
Thus the java program To add integers into a PriorityQueue and iterate over the elements using an iterator executed successfully.



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


