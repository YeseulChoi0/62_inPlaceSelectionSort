# in-place selection sort

Rearrange
an unordered `ArrayList<Integer>`
and use it as the data in an `OrderedList_inArraySlots`.

The re-use is probably contrary to Java's conventions
for its built-in classes. But as a pedagogical tool,
it has the advantage of allowing
the User program to check that the sort
is done in-place.

## count the cost

0. If the number of the elements in the input triples,
the time required to run the reigning champ algorithm
will grow by three times.

The reigning champ alogrithm is linear, and the time it will take is n (the size of the array).

0. If the number of the elements in the input triples,
the number of times that the reigning champ algorithm
will be invoked 
will grow by three times

The algorithm is linear so it will be invoked n times. 

0. If the number of the elements in the input triples,
the time required for the selection sort
will grow by a factor of 9.

Both algorithms are linear and for each of these n iterations, the reigning champ algorithm will also be called n times. Therefore, the time is around n squared (modified). 
