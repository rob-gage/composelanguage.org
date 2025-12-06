# `pick`

Copies the item at a specified index on the stack. Indexes wrap around the stack, and negative indexes start at the bottom of the stack.

`1 2 3 4 5 2 pick` → `1 2 3 4 5 3`

`false true 3 pick` → `false true false`

`1 2 3 4 5 -1 pick` → `1 2 3 4 5 1`
