# UMSATS C Coding Standard

This document is intended to be a living document. Add to this as needed.

# Rules

- Use CamelCase for function and variable names.
- Use 4 spaces for indentation.
- For header files, place the system includes first, and then the normal includes. They should be in alphabetical order otherwise. Example:
```C
#include <math.h>
#include <stdio.h>

#include "user_header1.h"
#include "user_header2.h"
```
- Place the first brace in the same line as a function. Example:
```C
void function() {
  //some code
}
```
- (Advisory) When working with *.ino files (i.e. Arduino), place as little code in the *.ino file as possible, and as much code into *.c and *.h files as possible. This is to make moving code from Arduino to the actual board as painless as possible.
