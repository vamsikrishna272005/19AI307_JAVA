# Ex.No:3(B) STRING BUFFER IN JAVA

## AIM:
To develop a java program to set the length of the character sequence equal to newLength using stringbuffer class.

## ALGORITHM :

1. Initialize `Scanner` and read a string input from the user.
2. Create a `StringBuffer` object using the input string.
3. Display the original length and contents of the `StringBuffer`.
4. Use `setLength(10)` to modify the length of the buffer.
5. Display the contents of the `StringBuffer` after resizing.

## PROGRAM:
 ```

Program to implement a String Buffer using Java
Developed by: Vamsi Krishna G
RegisterNumber:  212223220120

import java.util.*;

public class Demo{

	public static void main(String[] args)
	{
	    Scanner sc=new Scanner(System.in);
	    String str1=sc.nextLine();
		StringBuffer str = new StringBuffer(str1);
		System.out.println("String length = "+ str.length() +" and contains = " + str);
		str.setLength(10);
		System.out.println("After setLength() String = "+ str.toString());
	}
}

```

## OUTPUT:


![Screenshot 2025-05-09 135102](https://github.com/user-attachments/assets/2ca7fb2c-47f4-44a4-aaa9-26c3c2628c35)

## RESULT:
Thus the java program to set the length of the character sequence equal to newLength using stringbuffer class executed successfully.
