## Features
- Interpretate code (Will removed with isolated VM/Bytecode interpretation).
- Generate graph for the code ('.dot' graphviz)(May be removed later as redundancy).
- Compile (Generate) python code (GOFRA -> Python) (May be also removed later as redundancy or part of Bytecode2Python).
- Lint (Type check) [WIP].
- Bytecode (Compile, Interpretate) [WIP]

## Language features
- Stack implementation (push, pop)
- Conditional IFs ([bool_from_stack] if [code] else [code] end).
- WHILE loops (while [expression] do [code] end)
- Bytearray Memory (mbwrite, mbread, mbshowc, mbptr etc...)
- Characters, Strings.
- Basic I/O.

### Simple example
```
35 // Push 35 in the stack.
5 // Push 5 in the stack.
+ // Pop both 35 and 5, and push their sum in the stack.
show // Pop value from the stack and show it on the screen.
```
### Hello World example
```
"Hello, World!" mshowc
```

### [Documentation](https://github.com/gofra-lang/core/blob/main/DOCUMENTATION.md), [Examples](https://github.com/gofra-lang/core/tree/main/examples)
#### License MIT, [(c) 2022 Kirill Zhosul (Maintainer)](https://kirillzhosul.github.io/)
