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

