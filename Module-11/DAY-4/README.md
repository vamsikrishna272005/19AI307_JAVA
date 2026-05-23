# Ex.No:11(D) RELATED TO MAP CONCEPTS

## AIM:
To read key-value pairs from the user, store them in a HashMap, and display all entries.

## ALGORITHM :


1. **Take input `n`** – number of key-value pairs to be inserted.
2. **Create a `HashMap<Integer, String>`** to store integer keys and string values.
3. **Use a loop** to read `n` integer-string pairs from the user and insert them using `.put()`.
4. **Iterate over the map** using a `for-each` loop with `Map.Entry`.
5. **Print each key-value pair** using `getKey()` and `getValue()`.


## PROGRAM:
 ```
/*
Program to implement a RELATED TO MAP CONCEPTS using Java
Developed by: Vamsi krishna G
RegisterNumber: 212223220120

import java.util.*;
public class Demo{
    public static void main(String args[]){
        Scanner sc = new Scanner(System.in);
        Map<Integer,String> map = new HashMap<Integer,String>();
        int n = sc.nextInt();
        for(int i =0;i<n;i++){
            Integer a = sc.nextInt();
            String b = sc.next();
            map.put(a,b);
        }
        for(Map.Entry m: map.entrySet()){
            System.out.println(m.getKey()+" "+ m.getValue());
        }
    }
}
*/
```





## OUTPUT:

![Screenshot 2025-05-23 144849](https://github.com/user-attachments/assets/ce225056-85b6-4904-9c23-fb0037d15e50)


## RESULT:
Thus the java program To read key-value pairs from the user, store them in a HashMap, and display all entries executed successfully.


