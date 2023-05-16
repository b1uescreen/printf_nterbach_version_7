This is my own version of printf(), created for the "ft_printf" project at the coding school "42".
It only covers the most basic conversion functionality with the conversions cspdiuxX%. No options
or other features are implemented. The write() function is used to generate the output and writes
the whole result string at once.

Please note that characters written with the %c conversion will not be counted if their value
is -7 (integer value). Nullbytes can be written without any problems though.

The Makefile does not work without a "libft" source folder in its directory, which is not included
here (libft contains some custom C functions, mostly from the stdlib).

The code contained in this project does not depend on libft however, so you can still use it
in another library or program if you compile it yourself.
