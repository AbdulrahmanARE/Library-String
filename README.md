# libraryString (C++)

**A Lightweight C++ String Manipulation Library**  
This project is a custom C++ library designed to simplify common string operations through both static and object-oriented methods.

---

## Features

### Case Manipulation
- Convert strings to uppercase
- Convert strings to lowercase
- Invert letter case (A -> a, a -> A)
- Invert all letters' case in a string

### Counting & Statistics
- Count words in a string
- Count capital and small letters
- Count specific letters (with case sensitivity option)
- Count vowels (a, e, i, o, u)

### Formatting & Trimming
- Capitalize the first letter of each word
- Lowercase the first letter of each word
- Trim left, trim right, or trim both sides of a string
- Remove all punctuations from a string

### Advanced Operations
- Split strings into a vector of tokens based on a delimiter
- Join strings from a vector or array with a custom delimiter
- Reverse the order of words in a string
- Replace words within a string using built-in or custom split methods

---

## Purpose
This project is designed to practice and improve skills in:
- C++ Class design
- Static vs. Instance methods
- String and Vector handling
- Logic implementation for text processing

---

## How to Run
1. Download `clsString.h` and include it in your C++ project.
2. Use the `clsString` class by creating an object or calling its static methods.
3. Refer to `libraryString.cpp` for a complete demonstration of all available functions.
4. Compile your project using any C++ compiler (e.g., g++, Visual Studio).

---

## Sample Usage

```cpp
#include <iostream>
#include "clsString.h"
using namespace std;
int main() {
    // Using Object Methods
    clsString String1("abdulrahman ramadan");
    String1.UpperFirstLetterOfEachWord();
    cout << String1.Value << endl; // Output: Abdulrahman Ramadan

    // Using Static Methods
    cout << clsString::CountWords("Hello World from C++") << endl; // Output: 4

    return 0;
}
```

---

## Author
**Abdulrahman Ramadan** – A specialized C++ library for efficient string management and manipulation.
