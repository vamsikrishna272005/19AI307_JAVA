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
