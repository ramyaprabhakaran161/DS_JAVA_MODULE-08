# Ex15 Value Existence Check in a TreeMap
## DATE:23.3.26
## AIM:
To write a Java program that checks whether a given value exists in a TreeMap.

## Algorithm
```
1.Start the program.
2.Create a TreeMap and insert key–value pairs.
3.Use the containsValue() method to check if a specific value exists in the map.
4.Display whether the value is found or not.
5.Stop the program.
```

## Program:
```

Developed by: Ramya P
RegisterNumber: 212223230168 

```
```

import java.util.*;

public class TreeMapValueCheck {
    public static void main(String[] args) {
        TreeMap<Integer, String> map = new TreeMap<>();
        map.put(1, "Apple");
        map.put(2, "Banana");
        map.put(3, "Cherry");
        map.put(4, "Mango");

        System.out.println("TreeMap: " + map);
        String valueToCheck = "Banana";

        if (map.containsValue(valueToCheck))
            System.out.println("The value '" + valueToCheck + "' exists in the TreeMap.");
        else
            System.out.println("The value '" + valueToCheck + "' does not exist in the TreeMap.");
    }
}
```

## Output:


<img width="798" height="335" alt="image" src="https://github.com/user-attachments/assets/84432b7f-96ee-47e0-bfe5-f20a1ae89f48" />

## Result:
Thus, the program successfully checks whether a specified value exists in a TreeMap using the containsValue() method.
