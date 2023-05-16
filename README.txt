This is my own version of printf(). It only covers the most basic conversion functionality
with the conversions cspdiuxX%. No options or other features are implemented.
The write() function is used to generate the output and writes everything at once.
Please note that characters written with the %c conversion will not be counted if their value
is -7 (integer value). Nullbytes can be written without any problems though.

There are two different Makefiles for this project: One that creates a custom library
including this project as well as a custom version of the C standard library called "libft"
(which is not included here) and a standalone version that creates an executable with the
custom printf only.
