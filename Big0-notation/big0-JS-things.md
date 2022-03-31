Big 0 of Objects -

- insertion - 0(1)
- Removal - 0(1)
- Searching - 0(n)
- Access - 0(1)

Objects are fastest way to do thing in JS, but they are unordered.

Big 0 of Objects Methods -

- Object.keys - 0(n)
- Object.values - 0(n)
- Object.entries - 0(n)
- hasOwnProperty - 0(1)

Arrays - when to use them and pros and cons -

- When you need order
- When you need fast access/insertion and removal (sort of...)
- Insertion - depends...If you just push onto end of array it's 0(1) as it just adds that to index. But inserting at the front will be an 0(n) operation, as it needs to add the new entry but also reassign all the following indices to the previous entires (if Michael was [0], when Raj is added to front, Raj becomes [0] and Michael becomes [1] and so on)
- Removal - depends...For the same reasons stated above. Removing from back is 0(1) as it's constant, but from the front will be 0(n) for the same reason as above.
- Searching - 0(n) It needs to check every entry.
- Access - 0(1) It's constant, regardless of array size, because it doesn't count up to the number, it just goes directly there as it knows it's at location. So if it's [3], it goes right there just like if it was [9000].

Big 0 of Arrays Operations-

Push - 0(1)
Pop - 0(1)
Shift - 0(n)
Unshift - 0(n)
Concat- 0(n)
Slice - 0(n)
Splice - 0(n)
Sort - 0(n * log n)
forEach/map/filter/reduce/etc.- 0(n)
