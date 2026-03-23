# Ex11 Convert HashSet to ArrayList in Java
## DATE: 23/3/26
## AIM:
To convert a collection of distinct integers stored in a HashSet into an ArrayList and display its contents.
## Algorithm

1. Start the program.

2. Create a HashSet and add distinct integer elements to it.

3. Use the ArrayList constructor to convert the HashSet into an ArrayList.

4. Display the elements of both the HashSet and the ArrayList.

5. Stop the program.

## Program:

Developed by: Piritharaman R

RegisterNumber:  212223230148
```

import java.util.*;

public class HashSetToArrayList {
    public static void main(String[] args) {
        HashSet<Integer> set = new HashSet<>();
        set.add(10);
        set.add(20);
        set.add(30);
        set.add(40);
        set.add(50);

        System.out.println("HashSet: " + set);

        ArrayList<Integer> list = new ArrayList<>(set);
        System.out.println("ArrayList: " + list);
    }
}
```

## Output:

<img width="946" height="94" alt="image" src="https://github.com/user-attachments/assets/290ef7eb-3bea-405b-b817-9fe539d40d9f" />


## Result:
The program successfully converts a collection of distinct integers stored in a HashSet into an ArrayList
