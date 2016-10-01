# List of all commands

- cpl – C++
- jvpl – Java
- txpl – LaTeX

## cpl

**Language: C++**

#### Usage

    cpl [options] file

#### Options

- `-h`: Help
- `-o`: Compile the original file. More specifically, don't change `#include <bits/stdc++.h>` into `#include <allc++.h>` for compilation.
- `-g`: Compile for debugging. The executable will be prefixed with "d-". Will also compile one normal version.

## jvpl

**Language: Java**

#### Usage

    jvpl [options] file

#### Options

- `-h`: Help

#### Description

Compile the specified java file with the `javac` command.

The filename can be provided with or without extension.

## txpl

**Language: LaTeX**

#### Usage
    
    txpl file

#### Description

Compiles the specified file with the `latexmk` flag into a pdf.

The filename can be provided with or without extension.
