# Ex.No:9(A)          DATA I/O STREAM
## AIM:
To write data to multiple files using ByteArrayOutputStream, demonstrating the ability to write the same data to multiple output streams.
## ALGORITHM :

1. Create two `FileOutputStream` objects (`out` and `out2`) to write to `F1.txt` and `F2.txt`.
2. Create a `ByteArrayOutputStream` (`str`) to temporarily hold data in memory.
3. Use `write()` to write a byte (in this case, the value `69`, corresponding to the letter 'E') to the `ByteArrayOutputStream`.
4. Use `writeTo()` method of `ByteArrayOutputStream` to write the data from memory to both `FileOutputStream` objects (`out` and `out2`).
5. Close the `ByteArrayOutputStream` once the data is written to the files, then print `"Success..."` to indicate the operation completed.

## PROGRAM:
 ```
/*
Program to implement a DATA I/O STREAM using Java
Developed by: Vamsi Krishna G
RegisterNumber:  212223220120

FileOutputStream out = new FileOutputStream("F1.txt");
FileOutputStream out2 = new FileOutputStream("F2.txt");
ByteArrayOutputStream str = new ByteArrayOutputStream();
str.write(69);
str.writeTo(out);
str.writeTo(out2);
str.close();
System.out.println("Success...");
*/
```


## OUTPUT:

![Screenshot 2025-05-10 063658](https://github.com/user-attachments/assets/500d48b9-8986-48cf-ba59-745105a93f15)


## RESULT:
Thus the Java Program To write data to multiple files using ByteArrayOutputStream, demonstrating the ability to write the same data to multiple output streams executed successfully.


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












# Ex.No:9(D) TRANSIENT ---SERILIZATION

## AIM:
To deserialize a Studentinfo object from a file and display its name and rid.

## ALGORITHM :


1. **Declare a `Studentinfo` reference** initialized to `null`.
2. **Open `FileInputStream`** for `"student.txt"`.
3. **Create `ObjectInputStream`** to read objects from the file stream.
4. **Read and cast the object** to `Studentinfo` using `.readObject()`.
5. **Print deserialized values** (`name` and `rid`) and handle exceptions.


## PROGRAM:
 ```
/*
Program to implement a Transient using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

   Studentinfo si=null;
  try
        {
            FileInputStream fis = new FileInputStream("student.txt");
            ObjectInputStream ois = new ObjectInputStream(fis);
            si = (Studentinfo)ois.readObject();
        }
         catch (Exception e)
        {
            System.out.println(e);
            }
             System.out.println("Deserialization-Student Name:"+si.name);
            System.out. println("Deserialization-Student Rollno:"+si.rid);
       
           
 
*/
```

## OUTPUT:

![Screenshot 2025-05-23 141404](https://github.com/user-attachments/assets/c33eda8c-bc65-4da3-a819-d4ed7f966183)


## RESULT:
Thus, implementation of a Java program To deserialize a Studentinfo object from a file and display its name and rid executed successfully.


# Ex.No:9(E) Serialize Studentinfo Object to File
## AIM:
To serialize a Studentinfo object and write it to a file using ObjectOutputStream.
## ALGORITHM :

1. **Take user input** – Read `name` and `num` (roll number) using `Scanner`.
2. **Create a `Studentinfo` object** using the input values.
3. **Open a `FileOutputStream`** pointing to `"student.txt"` to store object data.
4. **Wrap it with `ObjectOutputStream`** and write the object using `.writeObject()`.
5. **Close the stream** and handle exceptions with try-catch.



## PROGRAM:
 ```
/*
Program to implement a STRING WRITER
Developed by: Vamsi krishna G
RegisterNumber: 212223220120

try{
    Scanner sc = new Scanner(System.in);
    String name = sc.nextLine();
    int num = sc.nextInt();
    Studentinfo obj = new Studentinfo(name,num);
    FileOutputStream fos = new FileOutputStream("student.txt");
    ObjectOutputStream obj1 = new ObjectOutputStream(fos);
    obj1.writeObject(obj);
    obj1.close();
}
catch(Exception e){
    System.out.println(e);
}
*/
```

## OUTPUT:

![Screenshot 2025-05-23 141652](https://github.com/user-attachments/assets/1b9ea630-c17f-4d96-aa32-ae95fac92b11)


## RESULT:
Thus, implementation of  a Java program To serialize a Studentinfo object and write it to a file using ObjectOutputStream executed successfully.

