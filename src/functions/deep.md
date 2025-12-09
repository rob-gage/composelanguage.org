# `deep`

Consumes an integer index and a lambda below it, and applies the lambda at that index in the stack. Indexes wrap around the stack, and negative indexes start at the bottom of the stack.

`1 2 3 4 5 ( copy * ) 2 deep` → `1 2 9 4 5`

`true false false ( copy copy ) -1 deep` → `true true true false false`

`1 2 3 4 5 ( drop drop ) 8 deep`  → `3 4 5`
