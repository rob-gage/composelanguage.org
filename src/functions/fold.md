# `fold`

Consumes a lambda, an accumulator value, and a list. Reduces the list from left to right by applying the lambda to the accumulator and each list item. The lambda must consume the accumulator and list item, and produce a new accumulator. The final accumulator value is produced on top of the stack.

`[ 1 2 3 4 ] 0 ( + ) fold` → `10`

`[ 1 2 3 4 ] 1 ( * ) fold` → `24`
