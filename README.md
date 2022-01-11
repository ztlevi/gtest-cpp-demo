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
lldb -S tests/gtest/.test-lldb-sample1
```

Run specific test

```sh
./build/tests/sample1_unittest --gtest_filter=FactorialTest.*
```

# CXX emacs lsp and dap setup
https://emacs-lsp.github.io/lsp-mode/tutorials/CPP-guide/
