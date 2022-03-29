# Big 0 Notation notes - Udemy

- Way of determining which code is the "best".
- May have some trade offs, slower up front, but earsier to scale. Faster to download, but requires more storage, etc.

### Timing Our Code -

- When given 2 different pieces of code, which is better? What does better mean? Faster, Less memory, more readable.
- Can write code to time both functions, but different machines run at differetn times, so results will vary. Even on the same machine, the time can vary.

### Counting our operations -

- Counting our operations is a way to stay consistent, as the computer will always perform those operations, ragardless of speed.
- An operation is something the computer performs, like adding, subtractig, multiplying, etc. Each operations adds 1 to the stack.
- In loop, the add function will perform once for each iteration (n times). As 'n' grows, so does the computational power needed and time/space.
- Can use a performance tracker to track time as well. Will show the time difference between the two algortihms on a graph. 'n' grows exponentionally as the number gets bigger.

What is Big 0? A way for us to talk the runtime for an algorithm growth as inputs grow. Don't care about the details, looking at trends. It looks at worst case senario.

If method is n + n it's referred to as n squared (n<sup>2</sup>).

### Simplifying Big 0 Expressions -

- Depending on what we count, the number of operations can be as low as 2n or as high as 5n + 2.
- But regardless of the exact number, the number of operations grows roughly proportionally with n.
- If n doubles, the number of operations will also roughly double.
- Constants don't matter. 0(2n) = 0(n); 0(500) = 0(1); 0(13n<sup>2</sup>) = 0(n<sup>2</sup>).
- Smaller terms don't matter. 0(n + 10) = 0(n); 0(1000n + 50) = 0(n); 0(n<sup>2</sup> + 5n + 8) = 0(n<sup>2</sup>).
- Big 0 Shorthand.
    1. Arithmetic operatioons are constant.
    2. Variable assignment is constant.
    3. Accessing elements in an array (by index) or object (by key) is constant.
    4. In a loop, the complexity is the length if the loop times the complexity of whatever happens inside of the loop.

### Space Complexity -

- How much memory is required. Auxiliary space complexity refers to space required by the algorithm, not including space taken by the inputs.
- Most primitives (Bools, numbers, undefined, null) are constant space.
- Strings require 0(n) space (where n is the string length).
- Reference types are generally 0(n), where n is the length (for arrays) or the number of keys (for objects).

Logarithms -

- An inverse of exponentiation. log<sub>2</sub>(8) = 3 --> 2<sub>3</sub> = 8; log<sub>2</sub>(value) = exponent --> 2<sub>exponent</sub> = value.
- The logarithm of a number roughly measures the number of times you can divide that number by 2 before you get a value that's less than or equal to one.
- We'll most likely see them in certain searching algorithms that have  logarithmic time complexity. Efficient sorting algorithms involve logarithms. Recursion sometimes invovles logarithmic space complexity.

Recap -

- To analyize the performance of an algorithm, we use Big 0 notation.
- Big 0 Notation can give us a high level understanding of the time or space complexity of an algorithm.
- Bog0 Notation doean't care about precision, only about general trwends(linear?, quadratic?, constant?).
- The time or space complexity (as measured by Big 0) depends ont eh algorithm, not the hardware used to run the algorithm.
