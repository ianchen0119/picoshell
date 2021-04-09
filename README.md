# picoshell

> A quiz of [linux 核心設計](https://hackmd.io/@sysprog/linux2021-quiz7/https%3A%2F%2Fhackmd.io%2F%40sysprog%2FSJ18gZYrO)

## issues
- [ ] stack smashing detected
In order to avoid this situation occurs, I use the `-fno-stack-protector` command when the source code be compiled.
but, I think it have a better solution, I still haven't found, for sure.

## How to Compile
```shell=
gcc -g -o main main.c -fno-stack-protector
```
