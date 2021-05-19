symbols.files.dat
=================

The
[symbols.files.dat](https://github.com/dmparrishphd/Shapiro-CORA/blob/main/Files/0/symbols.files.dat)
file maps certain files to the symbols defined therein.

Format
------

Each **comment** line begins with `#`.

Each **data** line is a space-delimited list that begins with the path (relative to the
directory of the
[Shapiro](https://github.com/dmparrishphd/Shapiro)
repository) to an R file.
The remaining items in the list are symbols defined in the file indicated.
Long lines are avoided by repeating the R file name on another line and continuing the list of symbols.
File paths and symbols may _not_ have embedded spaces.
