# Ex.No:2(A) CLASS AND OBJECT

## QUESTION:
Create a class Vehicle with attributes as number, type and owner.
## AIM:
To Create a class Vehicle with attributes as number, type and owner.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	





## PROGRAM:
 ```
/*
Program to implement a Class and Objects using Java
Developed by: DHANALAKSHMI S
RegisterNumber:  212222040033
*/

import java.util.Scanner;
class Vehicle{
    String number;
    String type;
    String owner;
}
public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        Vehicle v1 = new Vehicle();
        v1.number = sc.next();
        v1.type = sc.next();
        v1.owner = sc.next();

        Vehicle v2 = new Vehicle();
        v2.number = sc.next();
        v2.type = sc.next();
        v2.owner = sc.next();

        System.out.println(v1.number + " | " + v1.type + " | " + v1.owner);
        System.out.println(v2.number + " | " + v2.type + " | " + v2.owner);

        sc.close();
    }
}

```

## SOURCE CODE:







## OUTPUT:



## RESULT:

