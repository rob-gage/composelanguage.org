# `index`

Consumes a list and returns the item at a specified index. Indexes wrap around the list, and negative indexes start at the end of the list.

`[ 1 2 3 4 5 ] copy 2 index` → `[ 1 2 3 4 5 ] 3`

`[ 1 2 3 4 5 ] 5 index` → `1`

`[ 1 2 3 4 5 ] -1 index` → `5`
