# funny-cpp

Some facts of the C++ world, sometimes useful, sometimes not (mostly, impractical).

But, that doesn't make these fact less important, right?

## Contents

### 1. Move me

### 2. Really constexpr

### 3. Prime

### 4. Give me some privacy, please

### 5. To add constexpr or not to add

### 6. Simple array definition

This is perfectly valid C++ code:

  ```c++
  static constexpr int widths[] = { [0 ... 9] = 1, [10 ... 99] = 2, [100] = 3 };
  ```

### 7. Ordered tuple

### 8. Crazy int8_t

## Assumptions

1. I hope, all the code is compilable (more or less).

2. Code is written in C++17.

3. If you don't love C++, you won't like these pieces of code.
