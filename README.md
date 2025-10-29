### compile on Arch Linux with fish shell
```fish
eval g++ hello.cpp (wx-config --cppflags --libs) -o prog
```
- OR -
```fish
eval clang++ hello.cpp (wx-config --cppflags --libs) -o prog
```
