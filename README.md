# funny-cpp

WIP for a blog.

Some facts of the C++ world, sometimes useful, sometimes not (mostly, impractical).

But, that doesn't make these fact less funny, right?

## Contents

### 00. Simple array definition

This is perfectly valid C++ code:

  ```c++
  static constexpr int widths[] = { [0 ... 9] = 1, [10 ... 99] = 2, [100] = 3 };
  ```

### 01. Move me

### 02. Really constexpr

### 03. Prime

### 04. Give me some privacy, please

### 05. To add constexpr or not to add

### 06. Ordered tuple

### 07. Crazy int8_t

### 08. Hidden method

### 09. Dangling reference

### 10. Non-template STL

## Assumptions

1. I hope, all the code is compilable (more or less).

2. Code should almost always work in C++17.

3. If you don't love C++, you won't like these pieces of code.

4. No promises here.

5. Help is much appreciated.

6. I'm not a native speaker.
