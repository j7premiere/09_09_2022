### Task 8kyu
[Task link](https://www.codewars.com/kata/57cc975ed542d3148f00015b)

You will be given an array a and a value x. All you need to do is check whether the provided array contains the value.

Array can contain numbers or strings. X can be either.

Return true if the array contains the value, false if not.

### My solution
```Java
public class Solution {

    public static boolean check(Object[] array, Object value) {
        for (int i = 0; i < array.length; i++) {
            if (array[i].equals(value)) return true;
        }
        return false;
    }

}
```

### Favourite solution from code-wars

```Java
import java.util.Objects;

public class Solution {

    public static boolean check(Object[] a, Object x) {
        for (Object o : a) {
            if (Objects.equals(o, x)) {
                return true;
            }
        }
        return false;
    }

}
```

# Have a nice day!