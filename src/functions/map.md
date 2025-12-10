# `map`

Consumes a lambda, and a list below it, and produces the list with each item in it mapped using the lambda. The lambda must consume the original list item and produce a new one.

`[ 1 2 3 4 5 ] ( 2 * ) map` → `[ 2 4 6 8 10 ]`

`[ true false true ] ( ! ) map` → `[ false true false ]`
