# Ex.No:8(E)  File Writing with FilterOutputStream

## AIM:
To write a specified range of bytes from a string to a file using FilterOutputStream.
## ALGORITHM :
1. Create a `FileOutputStream` to open or create the file `testout.txt`.
2. Wrap the `FileOutputStream` with a `FilterOutputStream` to provide additional functionality for output.
3. Read a string from the user using `Scanner` and convert it to a byte array using `getBytes()`.
4. Prompt the user to enter two integers: `first` (the starting index) and `second` (the number of bytes to write).
5. Write a portion of the byte array (from `first` index to `first + second`) to the file using `filter.write(b, first, second)`.
6. Close both the `FilterOutputStream` and the `FileOutputStream` to release resources.

## PROGRAM:
 ```
/*
Program to implement a INPUT STREAM READER
Developed by: Vamsi krishna G
RegisterNumber: 212223220120

FileOutputStream files = new FileOutputStream("testout.txt");
FilterOutputStream filter = new FilterOutputStream(files);
Scanner sc = new Scanner(System.in);
String str = sc.nextLine();
byte[] b= str.getBytes();
int first = sc.nextInt();
int second = sc.nextInt();
filter.write(b,first,second);
filter.close();
files.close();
*/
```


## OUTPUT:

![Screenshot 2025-05-10 063250](https://github.com/user-attachments/assets/7fa7e44d-7667-46ba-b3ef-eb024bcaad78)


## RESULT:
Thus, the java program To write a specified range of bytes from a string to a file using FilterOutputStream executed successfully.

