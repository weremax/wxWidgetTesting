### compile on Arch Linux with fish shell
```fish
eval g++ main.cpp (wx-config --cppflags --libs) -o prog
```
- OR
```fish
eval clang++ main.cpp (wx-config --cppflags --libs) -o prog
```
