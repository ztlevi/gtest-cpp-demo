# GoogleTest

## Build

```sh
cmake -S . -B build
ln -s -f cmake-build-debug/compile_commands.json
cmake --build build --config Debug --target all -j 14 --
```

## Test example

```sh
lldb -S tests/.lldb-sample1
```
