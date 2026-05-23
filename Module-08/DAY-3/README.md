# Ex.No:8(C)             FILTER READER
## AIM:
To read a file, skip a certain number of bytes using skip(), and check the number of available bytes using available().

## ALGORITHM :

1. Create a `FileInputStream` to open the file `sample.txt`.
2. Wrap the `FileInputStream` with a `BufferedInputStream` (which extends `FilterInputStream`) to enhance file reading performance.
3. Use `Scanner` to take input from the user, specifying how many bytes to skip.
4. Use the `available()` method to check the number of bytes left to read in the file before and after skipping.
5. Close both the `FileInputStream` and `FilterInputStream` (BufferedInputStream) once the operations are complete.

## PROGRAM:
 ```
/*
Program to implement a Filter Reader using Java
Developed by: Vamsi Krishna G
RegisterNumber:  212223220120

    FileInputStream  file1 = new FileInputStream("sample.txt");  
        FilterInputStream filter = new BufferedInputStream(file1);  
        Scanner sc=new Scanner(System.in);
               int sk=sc.nextInt();
         System.out.println("Available bytes in the file: " +filter.available());
         filter.skip(sk);
          System.out.println("Available bytes in the file: " +filter.available());
  file1.close();  
        filter.close();  
 
            
      
*/
```


## OUTPUT:


![Screenshot 2025-05-10 062825](https://github.com/user-attachments/assets/cc589afa-f093-4435-8d37-825afe7ce68b)

## RESULT:
Thus the java Program To read a file, skip a certain number of bytes using skip(), and check the number of available bytes using available() executed successfully.









