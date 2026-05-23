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


