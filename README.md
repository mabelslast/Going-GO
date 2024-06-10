# Going-GO
Go Programming Notes

## General Program Structure Things
- Each program is organized into packages (modules or libraries)
- A package consists of one or more *.go* source files that tell the program what to do (contain the logic).
- Each .go file begins with a package declaration that indicates which package the file belongs to, followed by a list of other packages that it imports and then declarations of the program are stored in that file.
- The Go standard library contains over 100 packages for common tasks such as input and output, sorting and text manipulation.

  ```go fmt``` for instance contains functions for printing formatted output and scanning input.
  
- Package main is special, it defines a standalone executable program, not a library.
- Within package main, the main function is special, it defines the start of the program - where execution of the program begins.
- The import declaration, like ```go import fmt``` tells the compiler what packages are needed by the source file.
- Only exactly what packages are needed for the program must be imported or the program will not run.
- Declarations
  1. Import declarations must follow the package declaration. After that, the declaration of functions, variables, constants and types -> keywords func, var, const, and type.
- The ```os``` package provides functions and other values for dealing with the operating system in a platform independent fashion.
- Command-line arguments are available to a program in a variable named Args that is part of the ```os``` package, thus its name anywhere outside of the ```os``` package is ```os.Args```.
- 
