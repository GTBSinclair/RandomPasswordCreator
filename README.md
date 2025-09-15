# RandomPasswordCreator

A command-line tool to generate random and secure passwords

---

## Features

- Generates random passwords directly from the command line
- Customizable password **length** and **quantity**
- Designed for Windows

---

## Quick Start

### 1. Add to System Path

To use `RandomPasswordCreator` from any terminal window:

1. Locate the file `create_password.bat`
2. Add its folder path to the **Windows "Path" system environment variable**

> [Here’s how to add to the system PATH](https://www.architectryan.com/2018/03/17/add-to-the-path-on-windows-10/)

---

### 2. Usage

**Arguments:**

- `-n`: controls how many passwords to return  
- `-l`: controls the length of the passwords  
- `-o`: control the characters to omit from the passwords

Default command:
```bash
create_password
```
-n argument usage:

```bash
create_password -n 5
```
-l argument usage:

```bash
create_password -l 20
```
-o argument usage:

```bash
create_password -o *+^
```
using all arguments:

```bash
create_password -n 4 -l 18 -o %{°
```

## Changelog

[DEV]

[0000.001] First version [2025/09/15]

[MAIN]

[0000.001] First version [2025/09/15]