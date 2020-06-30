# fixedwidth2csv


## purpose
This program takes data that is in a fixed width format and converts into a CSV.

`gawk` has `FIXEDWIDTH` for this behavior, which you should use instead if you can get away with it.
 
However, `FIXEDWIDTH` requires you to either know the column sizes up front, or to figure them out yourself. This program does that for you.

More information can be found via `fixedwidth2csv -h`.

## requirements
`gawk` if you want to handle UTF-8 encoded data. Otherwise, any POSIX compatible `awk` is fine.

## installation
`curl -O https://raw.githubusercontent.com/mavenraven/fixedwidth2csv/master/fixedwidth2csv && chmod +x fixedwidth2csv`

## tests
To run the tests, run the following in the repo directory: `PATH=.:$PATH ./test_fixedwidth2csv`.
