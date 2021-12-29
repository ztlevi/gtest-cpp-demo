# GoogleTest

## Build

```sh
cmake -S . -B build
ln -s -f cmake-build-debug/compile_commands.json
cmake --build build --config Debug --target all -j 14 --
```

## Test example

- with ctest

```sh
cd build && ctest -j14 -C Debug -T test --output-on-failure
```

- with lldb

```sh
lldb -S tests/.lldb-sample1
```
