# Ex.No:8(A)           IO-FILE STREAM
## AIM:
To write a string to a file using FileOutputStream and handle resource closure using finally.

## ALGORITHM :

1. Define a string `data` to write into a file.
2. Initialize `FileOutputStream` to create or open the file `testout.txt`.
3. Convert the string to a byte array using `getBytes()`.
4. Write the byte array to the file using `f.write(b)`.
5. Ensure the file stream is closed in the `finally` block to prevent resource leaks.

## PROGRAM:
 ```
/*
Program to implement a IO File Stream using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120


        String data = "Welcome to Saveetha";
        FileOutputStream f = null;
        try{
            f = new FileOutputStream("testout.txt");
            byte[] b = data.getBytes();
            f.write(b);
            System.out.println("Successfully Completed");
          
        }
        finally{
            f.close();
        }
    
*/
```



## OUTPUT:

![Screenshot 2025-05-10 062228](https://github.com/user-attachments/assets/7207cdad-6123-4cde-ad1c-d2b1b35f31c7)


## RESULT:
Thus the Java Program To write a string to a file using FileOutputStream and handle resource closure using finally executed successfully.
