# Ex.No:10(A)         JAVA COLLECTION FRAMEWORK –ARRAY LIST
## AIM:
To read n integers from the user, store them in an ArrayList, and print each element.

## ALGORITHM:


1. **Take input `n`** – total number of integers to be entered.
2. **Create an `ArrayList<Integer>`** to store the integers.
3. **Use a loop** to read `n` integers from the user and add them to the list.
4. **Use an enhanced for-loop** to traverse the `ArrayList`.
5. **Print each integer** from the list on a new line.

## PROGRAM:
 ```
/*
Program to implement a ARRAY LIST using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120


import java.util.*;

public class Main { 
  public static void main(String[] args) { 
    ArrayList<Integer> myNumbers = new ArrayList<Integer>();
    Scanner sc=new Scanner(System.in);
    int n=sc.nextInt();
    for(int i=0;i<n;i++)
    {
    myNumbers.add(sc.nextInt());
    }
    for(int i:myNumbers){
        System.out.println(i);
    }
    
  } 
}

*/
```


## OUTPUT:


![Screenshot 2025-05-23 142141](https://github.com/user-attachments/assets/96fe1c9b-96c8-402c-9b1d-667deda735d2)

## RESULT:
TThus the Java Program To read n integers from the user, store them in an ArrayList, and print each element executed successfully.

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






# Ex.No:10(C)             JAVA LIST INTERFACE
 ## AIM :
To insert and update elements in a List<String> at specific indices using add() and set() methods.




## ALGORITHM :

1. **Take input `size`** – the number of strings to be initially added to the list.
2. **Create an `ArrayList<String>`** and populate it with user input.
3. **Display the list** to show the original content.
4. **Insert a new string at index 1** using `.add(1, value)`.
5. **Update the element at index 2** using `.set(2, value)` and print the modified list.

## PROGRAM:
 ```
/*
Program to implement a JAVA LIST INTERFACE using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

import java.util.*;


public class GFG {

	public static void main(String args[])
	{
		Scanner sc=new Scanner(System.in);
		List<String> al = new ArrayList<>();
        int size=sc.nextInt();
        for(int i=0;i<size;i++)
        {
				al.add(sc.next());
        }
        System.out.println(al);
        al.add(1,sc.next());
		
		System.out.println("After add element in index 1 :" + al);
		al.set(2,sc.next());
		System.out.println("After update:" + al);
	}
}

*/
```


## OUTPUT:

![Screenshot 2025-05-23 142927](https://github.com/user-attachments/assets/96b3cef0-7c23-479b-9b35-cf54f1f261bf)


## RESULT:
Thus the java program To insert and update elements in a List<String> at specific indices using add() and set() methods executed successfully.













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
