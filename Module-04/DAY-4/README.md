# Ex.No:4(D) FINAL & STATIC IN JAVA

## AIM:
 To create a company class using a constructor and display its details including a final ID.
## ALGORITHM :

1. Define a `Company` class with instance variables `name` and `add`, and a `final` variable `id` initialized to a constant value.
2. Create a constructor that accepts two parameters to initialize `name` and `add`.
3. Define a `print()` method to display the company ID, name, and address.
4. In the `main()` method, create an object of `Company` and pass values to the constructor.
5. Call the `print()` method to display the complete details of the company.


## PROGRAM:
 ```
/*
Program to implement a final & Static using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

class Company{
    String name,add;
    final String  id = "ED12G45";
    Company(String n , String a){
       name = n;
       add = a;
    }
    void print(){
        System.out.println("Company Details are,");
        System.out.println("Id is "+ id );
        System.out.println("Name is "+name);
        System.out.println("Address is "+add);
    }
}
public class Demo{
    public static void main(String ar[]){
        Company obj = new Company("ABC Foods","Chennai");
        obj.print();
    }
}
*/
```

## OUTPUT:

![Screenshot 2025-05-09 142955](https://github.com/user-attachments/assets/9f41f702-9269-47f2-9527-4f5a5a977f5a)


## RESULT:
Thus, the java program to create a company class using a constructor and display its details including a final ID.
