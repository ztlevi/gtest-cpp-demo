# GoogleTest

## Buile
``` sh
cmake -S . -B cmake-build-debug
cmake --build cmake-build-debug
ln -s -f cmake-build-debug/compile_commands.json
```

## Test example
``` sh
lldb -S tests/.lldb-sample1
```
