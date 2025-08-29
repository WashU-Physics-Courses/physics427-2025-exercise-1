## Exercise 1

Write a function that takes a vector of doubles and returns the sum of all the elements:

```cpp
#include <vector>

double sum(const std::vector<double>& a) {
    // Implementation here
}
```

Write some code to test that your function is implemented correctly. Put everything into `exercise1.cpp`.

        
## Exercise 2

Write a function that finds the maximum element in a vector of doubles:

```cpp
#include <vector>

double maximum(const std::vector<double>& a) {
    // Implementation here. The function should return the value of the maximum element
}
```

Again, write some code to test your function. Put everything into `exercise2.cpp`.

---

## Exercise 3

Write a function that adds two `std::vector`s together, and returns the result. Decide for yourself what is the signature of the function. You can either assume that the vectors are of type `double`, or make it a template function which can work for any type of vector.

Write some tests of your code to make sure it is working correctly. Put everything into `exercise3.cpp`.

---

## Exercise 4

Initialize a `std::vector<double>` with 1 million elements so that its `i`th element is equal to `i`.  
Then, write the content into a file. Put the code in `exercise4.cpp`.

**Question:** How much memory do you expect the vector to occupy? How large do you expect the output file to be? Is it the same size as what you expect?

You can write your answers to these questions in `exercise4.txt`.
