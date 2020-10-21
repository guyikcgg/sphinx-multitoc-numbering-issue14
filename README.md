# sphinx-multitoc-numbering / Issue #14 Reproducer

## Description
Reproducer of
https://github.com/executablebooks/sphinx-multitoc-numbering/issues/14

## Contents
Source (RST) and HTML output.

### Toplevel
See `.rst` files and contents of `part1`, `part2`, and `part3`.

### _build/html
See `index.html`:
```
Contents:

    Unumbered Chapter
    Part 1
        2. Chapter 1
        3. Chapter 2
    Part 2
        4. Chapter 3
    Part 3
        1. Chapter 4
```

## How to reproduce
Run the command:
```
make html
```
