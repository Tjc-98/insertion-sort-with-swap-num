# Insertion Sort with Swap Count

Insertion sort implementation in Java that displays each step of the sort and reports the total number of swaps performed.

---

## About

Written in Java, this program implements the insertion sort algorithm on an integer array. After each swap the current state of the array is printed, giving a step-by-step view of how the sort progresses. Once sorting is complete, the total number of swaps is reported. The algorithm is inspired by *Algorithms, 4th Edition* by Robert Sedgewick and Kevin Wayne.

## Usage

The program runs two back-to-back tests on startup:

1. **Interactive test** - prompts you to enter an array size and then each integer value. The array is sorted and the swap count is printed.
2. **Example test** - sorts the hard-coded array `{1, 2, 4, 3, 5, 0}` and prints the result.

Example session for the interactive test:

```
Enter the size of the array:
5
Enter the data:
3 1 4 1 5
Original Array:
{3, 1, 4, 1, 5}
Sorting:
...
The number of swaps performed: 3
```

## Getting Started

### Prerequisites

- Java 21 or later
- Apache Maven 3.8 or later

### Building

**Unix / macOS**
```bash
mvn package
```

**Windows**
```cmd
mvn package
```

### Running

**Unix / macOS**
```bash
java -cp target/InsertionSortWithSwapNum-1.0-SNAPSHOT.jar Main
```

**Windows**
```cmd
java -cp target\InsertionSortWithSwapNum-1.0-SNAPSHOT.jar Main
```

## Configuration

There are no environment variables. The only value you can tweak is directly in the source code:

| Constant / Value | Location | Description |
|---|---|---|
| `testArray2` | `Test.exampleTest()` in `Main.java` | The hard-coded array used by the example test. Change its contents to try a different fixed input. |

## License

MIT - see [LICENSE](LICENSE).
