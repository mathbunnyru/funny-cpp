# Ordered tuple

Do you know, that `std::tuple` can contain its elements in memory as it wants?
Try to implement a class, which contains its content in the right order.

For example `OrderedTuple<A, B, C>` has `A` object in the beginning, `B` in the middle and `C` in the end.

You need to add support for `std::get<size_t>(ordered_tuple)` and `tuple_size`.

Note: clang's libc++ does this right, but GCC's libstdc++ contains tuple in reversed order.
