# Ex.No:2(A)  STATIC METHOD

## AIM:
To calculate and display the area of a circle using a method.

## ALGORITHM :
1. Start the program and create a Scanner object for input.

2. Read the radius r as a double from the user.

3. Call the method calculateArea(r) to compute the area by squaring the radius.

4. Store and print the returned value with the message (currently labeled as "Area of square").

5. Close the scanner and end the program.


## PROGRAM:
 ```
Program to implement a Static method using Java
Developed by: Vamsi Krishna G
RegisterNumber:  212223220120

import java.util.Scanner;

public class AreaOfCircleMethod 

{
   public static void main(String[] args) 
   {
      Scanner sc = new Scanner(System.in);
      double r = sc.nextInt();
      double area = calculateArea(r);
      System.out.println("Area of square : " + area);
      sc.close();
   }

   static double calculateArea(double r)
   {
      return ( r * r);
   }
}
```

## OUTPUT:

![Screenshot 2025-05-09 112302](https://github.com/user-attachments/assets/5280fe7c-0aee-4bc4-b648-72f4ff8e7892)


## RESULT:
Thus , To calculate and display the area of a circle using a method is done successfully.

