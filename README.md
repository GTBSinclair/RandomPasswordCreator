# RandomPasswordCreator

A simple command-line tool to generate random and secure passwords using the Python Standard Library

---

## Features

- Generates random passwords directly from the command line
- Customizable password **length** and **quantity**
- Designed for Windows

---

## Quick Start

### 1. Add to System Path

To use `RandomPasswordCreator` from any terminal window:

1. Run `pip install random-password-creator` to install random-password-creator
2. Open a command prompt and type `password`. It should print a random password

---

### 2. Usage

**Arguments:**

- `-n`: controls how many passwords to return  
- `-l`: controls the length of the passwords  
- `-o`: controls the characters to omit from the passwords
- `-j`: outputs passwords only made up of letters and numbers
- `-a`: controls the characters to add to the passwords

Help message:

```
password -h
```
Default command:
```
password
```
-n argument usage:

```
password -n 5
```
-l argument usage:

```
password -l 20
```
-o argument usage:

```
password -o *+d
```
-j argument usage:

```
password -j
```
-a argument usage:

```
password -a !"£$%/()=?
```
using all arguments:

```
password -n 4 -l 15 -o *+d -j -a !\"£$%/()=
```

---


## Changelog

### [DEV]

[0000.006] Updated the main module [2026/01/11]\
[0000.005] Updated pyproject.toml and the main module [2025/12/28]\
[0000.004] Added the -a argument and removed the -i argument [2025/10/13]\
[0000.003] Added the -j argument [2025/10/04]\
[0000.002] Added the -i argument [2025/09/23]\
[0000.001] First version [2025/09/15]

### [MAIN]

[0000.006] Updated the main module [2026/01/11]\
[0000.005] Updated pyproject.toml and the main module [2025/12/28]\
[0000.004] Added the -a argument and removed the -i argument [2025/10/13]\
[0000.003] Added the -j argument [2025/10/04]\
[0000.002] Added the -i argument [2025/09/23]\
[0000.001] First version [2025/09/15]