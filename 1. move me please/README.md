# Move me please

Consider following code:

```c++
#include <iostream>

struct Big {
  Big() { std::cout << "ctor\n"; }
  Big(const Big&) { std::cout << "copy\n"; }
  Big(Big&&) { std::cout << "move\n"; }
};

void foo(Big big) {}

int main() {
  Big v;
  auto lambda = [big=std::move(v)] { foo(std::move(big)); };

  lambda();
  return 0;
}
```

Does this code works exactly as it looks like?
