Hello
```java runnable
// { autofold
import java.util.Arrays;
import java.util.List;
import java.util.stream.Collectors;

public class Main {

public static void main(String[] args) throws Exception {

// }

List<Integer> integers = Arrays.asList(1, 2, 3, 4, 5);

List<Integer> newIntegers = integers.stream()
    .filter(i -> i <= 3)
    .map(i -> 2*i)
    .collect(Collectors.toList());

System.out.println(newIntegers);

// { autofold

}

}

// }
```
