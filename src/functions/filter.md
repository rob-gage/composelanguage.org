# `filter`

Consumes a lambda, and a list below it, and produces a list containing only items from the original list for which the lambda produces `true`. The lambda must consume the original list item and produce a boolean.

`[ 1 2 3 4 5 6 7 8 9 10 ] ( 2 % 0 = ) filter` → `[ 2 4 6 8 10 ]`

`[ true false true ] ( true = ) filter` → `[ true true ]`
