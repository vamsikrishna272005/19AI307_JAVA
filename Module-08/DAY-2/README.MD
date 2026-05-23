# Ex.No:8(B) IO-FILE READER/WRITER
## AIM:
To read characters from a string using StringReader and store them in a character array.

## ALGORITHM :

1. Define a string `str` to read from.
2. Create a `char` array `array` to store the read characters.
3. Use `StringReader` to wrap the string and read its contents into the character array.
4. Call `r.read(array)` to read characters from the string into the array.
5. Print the characters stored in the array, handling any potential exceptions.



## PROGRAM:
 ```
/*
Program to implement a IO File Reader/Writer using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

import java.util.*;
import java.io.*;
public class Demo{
    public static void main(String args[]){
    String str = "WELCOME ALL.";
    char[] array = new char[12];
      try
      {
          Reader r = new StringReader(str);
         r.read(array);
         System.out.println("Data read from the string:");
         System.out.println(array);
      }
   catch(Exception e){
                    System.out.println(e);}
    }
                    
}
*/
```


## OUTPUT:


![Screenshot 2025-05-10 062621](https://github.com/user-attachments/assets/cf313115-0581-4ec6-b740-6eb137e1e1f4)

## RESULT:
Thus, the java program To read characters from a string using StringReader and store them in a character array executed successfully.



