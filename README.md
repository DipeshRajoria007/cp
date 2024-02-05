# README for C++ Template File

This README document provides an overview of the included C++ template file. The template is designed to streamline the process of writing C++ programs, especially for competitive programming or quick scripting tasks. It incorporates various preprocessor directives, macros, and type definitions to reduce boilerplate code and enhance coding speed.

## Features

- **Fast Input/Output**: Utilizes `ios_base::sync_with_stdio(0), cin.tie(0), cout.tie(0);` for faster I/O operations, reducing the time taken for large input/output operations, which is critical in competitive programming.

- **Loop Macros**: Defines macros for increasing and decreasing loops (`incr_loop`, `decr_loop`), including nested loops, to simplify the syntax and improve readability.

- **Type Definitions**: Includes type definitions for common data types such as `long long` as `ll`, `vector<int>` as `vi`, `vector<long long>` as `vll`, `pair<int, int>` as `pii`, and several others to shorten the code and make it more readable.

- **Utility Macros**: Contains macros for common operations such as `pb` for `push_back`, `ppb` for `pop_back`, `MP` for `make_pair`, and functions like `gcd` for the greatest common divisor, among others.

- **Predefined Constants**: Defines constants for `PI`, `mod` (set to 10^9 + 7), and `inf` (set to 1e18), which are frequently used in mathematical computations and algorithms.

- **Sorting and Searching Utilities**: Includes macros for sorting (`sort_all`), and functions for binary search (`bs`), lower and upper bound (`lb`, `ub`).

- **Main Function Template**: Provides a skeleton for the `main` function, including a loop for running multiple test cases, which is a common pattern in competitive programming problems.

## Usage

To use this template, copy the provided code into your C++ source file. You can then add your algorithm or logic inside the `solve` function or directly within the `main` function, depending on your preference. The template is flexible and can be modified to suit different programming needs.

### Customization

- **Test Cases**: Uncomment `cin >> t;` if the problem requires reading the number of test cases from the input.

- **Function Implementations**: Implement your solution in the `solve` function or directly inside the `main` loop for single-test case problems.

- **Additional Libraries**: Include any specific headers or libraries as per the problem requirements.

## Note

This template uses some advanced C++ features and shortcuts to optimize for speed and efficiency, which might not be suitable for beginners. Understanding the implications of each macro and type definition is recommended for effective use.

## Disclaimer

The template is provided "as is" for convenience and should be adapted to fit the specific requirements of your problem or coding environment.
