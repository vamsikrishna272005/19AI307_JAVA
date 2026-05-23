# Ex.No:9(B) BYTE ARRAY I/O
## AIM:
To skip a bytes in a byte array input stream and print the remaining bytes.

## ALGORITHM :

1. **Take input `a`** – number of bytes to skip.
2. **Initialize byte array** – `{1, 2, 3, 4}` and create `ByteArrayInputStream`.
3. **Skip `a` bytes** using `.skip(a)` method.
4. **Read and print** remaining bytes using `.read()` in a loop.
5. **Handle exceptions** and close the stream properly.



## PROGRAM:
 ```
/*
Program to implement a BYTE ARRAY I/O using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

import java.io.ByteArrayInputStream;
import java.util.*;
public class Main {
  public static void main(String[] args) 
  {
      Scanner sc = new Scanner(System.in);
      int a = sc.nextInt();
      byte[] arr= {1,2,3,4};
      try
      {
          ByteArrayInputStream b = new ByteArrayInputStream(arr);
          b.skip(a);
          System.out.print("Input stream after skipping "+ a+"  bytes: ");
          int data = b.read();
          while(data!=-1){
              System.out.print(data+", ");
              data = b.read();
          }
        b.close();
      
      

    }

    catch(Exception e) {
      e.getStackTrace();
    }
  }
}
*/
```

## OUTPUT:
![Screenshot 2025-05-23 140657](https://github.com/user-attachments/assets/6523f89c-4239-4438-ab51-c18253feb2ac)



## RESULT:
Thus, java program To skip a bytes in a byte array input stream and print the remaining bytes executed successfully.





