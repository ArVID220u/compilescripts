# List of all commands

- cpl – C++
- txpl – LaTeX

## cpl

**Language: C++**

#### Usage

    cpl [options] file

#### Options

- `-h`: Help
- `-o`: Compile the original file. More specifically, don't change "#include <bits/stdc++.h>" into "#include <allc++.h>" for compilation.
- `-g`: Compile for debugging. The executable will be prefixed with "d-". Will also compile one normal version.

#### Description

Compiles with the command `g++-5`, thus presuming a GCC compiler of version 5. Compile flags will include `-std=c++11`, and compiled file will be saved with the name of the original file minus the `.cpp` extension.

The filename can be provided with or without extension.

## txpl

**Language: LaTeX**

#### Usage
    
    txpl file

#### Description

Compiles the specified file with the `latexmk` flag into a pdf.

The filename can be provided with or without extension.
