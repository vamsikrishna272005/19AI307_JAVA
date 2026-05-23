# Ex.No:3(A)  STRING AND ITS OPERATIONS IN JAVA
## AIM:
To compare three input strings using case-insensitive comparison in Java.

## ALGORITHM :
1. Initialize Scanner and read three strings from user input.
2. Store the input strings in `str1`, `str2`, and `str3`.
3. Compare `str1` and `str2` using `equalsIgnoreCase()` and print the result.
4. Compare `str1` and `str3` using `equalsIgnoreCase()` and print the result.
5. Compare `str2` and `str3` using `equalsIgnoreCase()` and print the result.

## PROGRAM:
 ```
Program to implement a String and its Operations using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

import java.util.*;
public class Demo{
    public static void main(String args[]){
        Scanner sc = new Scanner(System.in);
        String str1 = sc.nextLine();
        String str2 = sc.nextLine();
        String str3 = sc.nextLine();
        
        System.out.println(str1.equalsIgnoreCase(str2));
        System.out.println(str1.equalsIgnoreCase(str3));
        System.out.println(str2.equalsIgnoreCase(str3));
        
    }
}

```

## OUTPUT:


![Screenshot 2025-05-09 134816](https://github.com/user-attachments/assets/780c6667-35b3-404d-acd5-5599fe6544d8)

## RESULT:
Thus the java Program to compare three input strings using case-insensitive comparison in Java executed successfully.


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

# Ex.No:3(C)    STRING BUILDER IN JAVA

## AIM:
To Create a java program to convert string into a character array and display it in a specific format.
## ALGORITHM :

1. Initialize `Scanner` and read a string input from the user.
2. Convert the string to a character array using `toCharArray()`.
3. Determine the length of the character array.
4. Loop through the array, printing each character with a comma separator.
5. Display the character array in the format `[char1, char2, ..., charN]`.

## PROGRAM:
 ```
Program to implement a String Builder using Java
Developed by: Vamsi Krishna G
RegisterNumber:  212223220120

import java.util.*;
public class Demo{
    public static void main(String args[]){
        Scanner sc = new Scanner(System.in);
        String str1 = sc.nextLine();
        char[] arr = str1.toCharArray();
        int n = arr.length;
        System.out.print("[");
        for(int i =0;i<n;i++){
            System.out.print(arr[i]);
            if (i < n - 1) {
                System.out.print(", ");
            }
        }
        System.out.print("]");
    }
}
```


## OUTPUT:

![Screenshot 2025-05-09 135323](https://github.com/user-attachments/assets/fbe70b98-607c-43dd-8a93-3a0fac08e7dd)


## RESULT:
Thus the java program to convert string into a character array and display it in a specific format executed successfully.




# Ex.No:3(D) STRING TOKENIZER IN JAVA

## AIM:
To tokenize a string using multiple delimiters and display each token in Java.

## ALGORITHM :

1. Initialize `Scanner` and read a string input from the user.
2. Create a `StringTokenizer` object with the input string and delimiters `://.`.
3. Check if there are more tokens available using `hasMoreTokens()`.
4. Use `nextToken()` to retrieve and display each token one by one.
5. Continue the process until all tokens are displayed.


## PROGRAM:
 ```

Program to implement a String Tokenizer using Java
Developed by: Vamsi Krishna G
RegisterNumber:  212223220120

import java.util.*;

public class Demo{
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String str= sc.nextLine();
        StringTokenizer t= new StringTokenizer(str, "://.", true);

        while (t.hasMoreTokens()) {
            System.out.println(t.nextToken());
        }
    }
}

```

## OUTPUT:
![Screenshot 2025-05-09 135612](https://github.com/user-attachments/assets/ce8dd089-1161-4cd5-b8b8-ac07ebf3c661)



## RESULT:
Thus the java program To tokenize a string using multiple delimiters and display each token in Java executed successfully.

# Ex.No:3(E) Array Input and Display

## AIM:
To take input for two integer arrays and display their elements in Java.

## ALGORITHM :
1.	Start the program.
2.	Declare and initialize a string variable str1.
3.	Create a StringBuilder object by passing str1 to its constructor.
4.	Store the object reference in the variable sb.
5.	Print the contents of sb to verify the output.
6.	End the program.


## PROGRAM:
 ```
/*
Program to implement a StringBuilder Object Reference in Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

import java.util.*;
public class DEmo{
    public static void main(String a[]){
        Scanner sc = new Scanner(System.in);
        int[] arr = new int[5];
        for(int i =0;i<5;i++){
            arr[i] = sc.nextInt();
            System.out.println(arr[i]);
        }
        int[] arr2 = new int[5];
        for(int i=0;i<5;i++){
            arr2[i] = sc.nextInt();
            System.out.println(arr2[i]);
        }
    }
}
*/
```

## OUTPUT:


![Screenshot 2025-05-09 135803](https://github.com/user-attachments/assets/7569e6a8-9d4c-42f0-8114-1b37d93e75a7)

## RESULT:
Thus the  Java program successfully to take input for two integer arrays and display their elements in Java is executed successfully.


