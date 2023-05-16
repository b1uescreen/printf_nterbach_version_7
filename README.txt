This is my own version of printf(). It only covers the most basic conversion functionality
with the conversions cspdiuxX%. No options or other features are implemented.
The write() function is used to generate the output and writes the whole result string at once.

Please note that characters written with the %c conversion will not be counted if their value
is -7 (integer value). Nullbytes can be written without any problems though.

The Makefile needs a "libft" source folder in its directory to work and creates a library
containing libft as well as "ft_printf" (the official name of this project).

The code contained in this project does not depend on libft however, so you can still use it
in another library or program if you compile it yourself.
