matches
=======

Usage
-----

_forthcoming_

| Argument | Description     |
| -------: | :-------------- |
|    `...` | passed to match |

Details
-------

The `matches` function is similar to `match`.
The `Table` argument has two columns.
The first column corresponds to the `table` argument of `match`;
The `matches` function applies `match` to the first column of `Table` and
uses the result to extract values from the second column of `Table`,
returning the extracted values.

Examlpes
--------

    matches(0:15, cbind(0:15, strsplit("0123456789ABCDEF", "")[[1]]))
    # [1] "0" "1" "2" "3" "4" "5" "6" "7" "8" "9" "A" "B" "C" "D" "E" "F"'
    
Code
----

["126"](https://github.com/dmparrishphd/Shapiro/blob/master/Files/1/2/6/0/matches.R)
