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












