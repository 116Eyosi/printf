<h1> printf </h1>

<h2> Usage</h2>
<ul>
<li>```c</li>
<li>#include "holberton.h"</li>
</ul>
// ...

_printf("%c", "H");
_printf("%s", "Bienvenue chez vous");
_printf("%r", "Holberton");
_printf("%R", "adrien");

// ...
```

<h2>Will display:</h2>
<ul>
<li>```shell</li>
<li>H</li>
<li>Bienvenue chez vous</li>
<li>notrebloH</li>
<li>nqevra</li>
```

<h2> Files </h2>

<h3> arg_nbr_functions.c & arg_nbr_functions_1.c </h3>

## This file corresponds to every functions used to manipulate number arguments.

<h3> arg_str_functions.c</h3>

## This file corresponds to every functions used to maninipulate string argument.

<h3> conversion.c</h3>

## This file corresponds to every functions used to convert number, string, pointer.

- int convert_alpha_numeric(int nb, int upper)
- char *convert_base(unsigned long nb, unsigned int base, int upper)
- char *convert_base_pointer(void *p)
- char *convert_rot13(char *str)

<h3>numbers.c</h3>

## This file corresponds to every basic number functions.

- int print_unsigned_number(unsigned int n)
- int print_number(int n)
- int _nbr_len(int prmNumber)
- char *_itoa(int prmNumber)

<h3> strings.c</h3>

## This files corresponds to every basic string functions.

- int _putchar(char c)
- int _puts(char *str, int ascii)
- int _strlen_recursion(char *s)
- char *_strdup(char *str)

<h2>Authors</h2>
## Eyosiyas Nigussie <br>
## Teddy Omondi
