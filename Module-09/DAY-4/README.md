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

