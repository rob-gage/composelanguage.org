# `fold`

Consumes a lambda, a list, and an accumulator value. Reduces the list from left to right by applying the lambda to the accumulator and each list item. The lambda must consume the accumulator and list item, and produce a new accumulator. The final accumulator value is produced on top of the stack.

`0 [ 1 2 3 4 ] ( + ) fold` → `10`

`1 [ 1 2 3 4 ] ( * ) fold` → `24`
