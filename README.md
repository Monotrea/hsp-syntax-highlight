# hsp-syntax-highlight README

## Features

This is a simple syntax-highlight extension for HSP.  

## Requirements

For Visual Studio Code Users.

## Extension Installation

Go to the Extension Tab on your VS Code.  
Then Select "Install from VSIX files", and Install `hsp-syntax-highlight-0.0.1.vsix`.

## Known Issues

I tried to highlight orders and their parameters without considering HSP keywords like "mes".
This enables us to highlight both HSP built-in functions and user-defined functions.
However, special highlights on HSP keywords might be necessary...
This highlight can't indentify order, parameter and variable name in #define context...
Such as...

```
#define hoge 1
#define fuga hoge
#define piyo redraw
```

If you find any problems, please feel free to create an issue.

## Release Notes

### 0.01

Standard Syntax Highlight function for .hsp files.

