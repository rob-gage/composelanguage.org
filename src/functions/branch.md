# `?`

Consumes two lambdas from the top of the stack, and a boolean below them. If the boolean is true, the bottom lambda is applied to the stack, and if it is false, the top lambda is applied to the stack.

`5 false ( 2 * ) ( 2 + ) ?` → `7`

`5 true ( 2 * ) ( 2 + ) ?` → `10`
