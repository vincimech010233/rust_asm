# Rust, C, and Assembly Exercises

[Español](README.es.md)

A learning archive of low-level programming exercises in Rust notebooks, C harnesses, and x86-64 assembly.

The assembly directories pair small routines with C programs so behaviour can be inspected and compared. Exercises cover arithmetic, strings, branching, input handling, and simple kata-style problems.

## Build example

Requirements depend on the exercise and typically include a C compiler and NASM. A representative workflow is:

```bash
nasm -f elf64 exercise.asm -o exercise.o
gcc -no-pie main.c exercise.o -o exercise
./exercise
```

Verify filenames and exported symbols for the selected directory.

## Limitations

These are independent learning exercises without a unified build system or automated test suite. Review memory handling and platform assumptions before reuse.

## License

No repository-wide license has been selected.
