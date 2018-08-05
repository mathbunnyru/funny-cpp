# To add constexpr or not to add - answer

Let's consider following piece of code:

```c++
#include <iostream>

int f() { return 3; }

const int a = f();

int main() {
  int x = a + 1;
  std::cout << x;
}
```

In this code it's obvious for people, that x is always 4 (and therefore it can be optimized).
Now, try it in clang or GCC [here](https://gcc.godbolt.org).

And after that change `f` to be constexpr.
You would be surprised, but your code got faster.
