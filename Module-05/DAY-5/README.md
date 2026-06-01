# Ex.No:5(E) HAS-A RELATIONSHIP
## AIM:
To implement a  Java Program to Find the Largest or Max Number in Array using has - a relationship.
## ALGORITHM :
1.	Start the program.
2.	Create a class ArrayData:
a.	Declare an integer array and a variable for size.
b.	Create a method to read array elements from the user.
3.	Create another class ArrayOperation:
a.	Create a method findMax() that accepts an ArrayData object.
b.	Loop through the array and find the largest element.
4.	In the main() method of a class Main:
a.	Create an object of ArrayData and read the input.
b.	Create an object of ArrayOperation and call findMax() by passing the ArrayData object.
5.	Display the largest number.
6.	End the program.



## PROGRAM:
 ```
/*
Program to implement a HAS-A RelationShip
Developed by: NIVESH N K
RegisterNumber:  212224050027
*/
```

## Sourcecode.java:

```
import java.util.Scanner;

class ArrayData {
    int arr[];
    int size;

    void readData() {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter size of array: ");
        size = sc.nextInt();

        arr = new int[size];

        System.out.println("Enter array elements:");
        for (int i = 0; i < size; i++) {
            arr[i] = sc.nextInt();
        }
    }
}

class ArrayOperation {

    void findMax(ArrayData data) {
        int max = data.arr[0];

        for (int i = 1; i < data.size; i++) {
            if (data.arr[i] > max) {
                max = data.arr[i];
            }
        }

        System.out.println("Largest number is: " + max);
    }
}

public class Main {
    public static void main(String[] args) {
        ArrayData obj1 = new ArrayData();
        obj1.readData();

        ArrayOperation obj2 = new ArrayOperation();
        obj2.findMax(obj1);
    }
}
```





## OUTPUT:
<img width="590" height="285" alt="image" src="https://github.com/user-attachments/assets/c952ea0d-563d-437b-bf46-16b9a339f595" />




## RESULT:
Thus the java program to Find the Largest or Max Number in Array using has - a relationship was executed successfully. 

