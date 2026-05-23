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


