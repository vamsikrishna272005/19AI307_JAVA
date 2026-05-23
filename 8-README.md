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










# Ex.No:8(D) BUFFER INPUT/OUTPUT STREAM

## AIM:
To read student details (name, department, and roll number) from the user and display them using a custom Student class.
## ALGORITHM :

1. Create a `Student` class with a constructor that initializes the `name`, `dept`, and `rollno` fields.
2. Define a `displayDetails` method in the `Student` class to print the student's details.
3. In the `main` method, instantiate a `BufferedReader` to read user input for `name`, `dept`, and `rollno`.
4. Convert the `rollno` input to an integer using `Integer.parseInt()` since `BufferedReader` reads input as a string.
5. Create a `Student` object with the provided details and call `displayDetails()` to show the information.

## PROGRAM:
 ```
/*
Program to implement a Buffer Input/Output Stream using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

 import java.io.BufferedReader;
import java.io.IOException;
import java.io.InputStreamReader;
class Student{
String name;
int rollno;
String dept;
Student(String name, String dept, int rollno){
this.name = name;
this.dept = dept;
this.rollno = rollno;
}
public void displayDetails(){
System.out.println("Name: "+this.name);
System.out.println("Department: "+this.dept);
System.out.println("Rollno: "+this.rollno);
}
}
public class ReadData {
public static void main(String args[]) throws IOException {
BufferedReader reader =new BufferedReader(new InputStreamReader(System.in));

String name = reader.readLine();

String dept = reader.readLine();

int rollno = Integer.parseInt(reader.readLine());
Student std = new Student(name, dept, rollno);
std.displayDetails();
}
}
*/
```

## OUTPUT:


![Screenshot 2025-05-10 063008](https://github.com/user-attachments/assets/88bb44dc-370b-4ff7-a0a6-a0c55ae97b6f)

## RESULT:
Thus, the java program To read student details (name, department, and roll number) from the user and display them using a custom Student class executed successfully.



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

