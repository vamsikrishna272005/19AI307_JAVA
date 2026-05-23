# Ex.No:6(A)  INNER CLASS
## AIM:
To demonstrate accessing outer class members using a non-static inner class in Java.

## ALGORITHM :

1. Define an outer class `Employee` with private attributes `Emp_Id` and `Emp_Name`.
2. Create a non-static inner class `Salary` that contains salary-related fields.
3. Implement a `display` method in the inner class to print employee details and total salary.
4. In the `main` method, create an instance of the outer class `Employee`.
5. Use the outer class instance to create the inner class object and call the `display` method.

## PROGRAM:
 ```
/*
Program to implement a Inner Class using Java
Developed by: Vamsi Krishna G
RegisterNumber: 212223220120

class Employee {
    private String Emp_Id = "EMP123";
    private String Emp_Name = "John";

    class Salary {
        private float Basic = 22500;
        private float Allowance = 2300;

        public void display() {
            System.out.println(Emp_Id + " " + Emp_Name  + " "+(Basic + Allowance));
        }
    }
}

public class Main {
    public static void main(String[] args) {
        Employee emp = new Employee();
        Employee.Salary obj = emp.new Salary();
        obj.display();
    }
}

*/
```

## OUTPUT:

![Screenshot 2025-05-10 055702](https://github.com/user-attachments/assets/84ecf805-8801-4829-b0c3-de887fe88f39)


## RESULT:
Thus, the Java Program To demonstrate accessing outer class members using a non-static inner class in Java executed successfully.

