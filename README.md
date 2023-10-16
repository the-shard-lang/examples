# Examples
### Reversing array
```cs
import Examples;

fun main() {
  var array = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11]; // use type deducation for cleaner code
  var reversed = reverse(array);
  
  Console.write(reversed); // [11, 10, 9, 8, 7, 6, 5, 4, 3, 2, 1]
}

export Examples {
  fun reverse(int[] array): int[] {
    var output: int[];
    for element in array {
      output.push(0, element); // add element to the start of an array
    }
  
    return output;
  }
}
```
