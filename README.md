# Printf

The `printf` project is a custom implementation of the `printf` function in C. It provides a formatted output to the standard output stream or a string.

## Features

- Supports formatting for various data types, including integers, floating-point numbers, strings, characters, and more.
- Implements various format specifiers such as `%d`, `%f`, `%s`, `%c`, `%x`, `%o`, and more.
- Handles width and precision specifications.
- Supports flags like `+`, `-`, `0`, `#`, and space.
- Handles variable-length argument lists using the `va_list` type and macros from the `<stdarg.h>` library.
- Provides a versatile and customizable alternative to the standard `printf` function.

## Usage

To use the `printf` function in your C program, include the `printf.h` header file:

```c
#include "main.h"
```

Then, you can call the `printf` function to output formatted text:

```c
printf("Hello, %s!\n", "World");
```

You can also store the formatted output into a string using the `sprintf` function:

```c
char buffer[100];
sprintf(buffer, "The value of pi is approximately %.2f", 3.14159);
```

## Building and Running

To build the `printf` project, compile the source files using your preferred C compiler:

```bash
gcc -o printf printf.c main.c
```

Then, run the generated executable:

```bash
./printf
```

## Contributing

Contributions to the `printf` project are welcome! If you find any issues or want to suggest improvements, please feel free to submit a pull request or open an issue in the project repository.

## License

This project is licensed under the [MIT License](LICENSE).

---
