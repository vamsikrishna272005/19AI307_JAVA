# Ex.No:9(C)             STRING READER
## AIM:
To write input string data to a StringWriter and display it.


## ALGORITHM :
1. **Take input** string from the user using `Scanner`.
2. **Create `StringWriter`** with default buffer.
3. **Write the input** string to the `StringWriter` using `.write()`.
4. **Print the content** stored in the `StringWriter`.
5. **Handle exceptions** and close the `StringWriter`.


## PROGRAM:
 ```
/*
Program to implement a String Reader using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

import java.io.StringWriter;
import java.util.*;
public class Main {
  public static void main(String[] args) {

   Scanner sc = new Scanner(System.in);
    String data = sc.nextLine();

    try {
      // Create a StringWriter with default string buffer capacity
      System.out.print("Data in the StringWriter: ");
      StringWriter output = new StringWriter();
      output.write(data);
      System.out.println(output);
      output.close();
      
      
      
    }

    catch(Exception e) {
      e.getStackTrace();
    }
  }
}
*/
```



## OUTPUT:


![Screenshot 2025-05-23 141050](https://github.com/user-attachments/assets/73a66dc4-3e6c-48ba-afd0-f64f7721d9f1)

## RESULT:
Thus the Java Program To write input string data to a StringWriter and display it executed successfully.











