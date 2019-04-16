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
will grow by a factor of three. There are three times as
many elements to iterate through, and since the reigning
champ method is linear the growth is a factor of three.
[Justify, in about 2 sentences.]

0. If the number of the elements in the input triples,
the number of times that the reigning champ algorithm
will be invoked will grow by a factor of three. Each
new element means an invocation of the reigning champ
method, and three times the elements means three times
the invocations.
[Justify, in about 2 sentences.]

0. If the number of the elements in the input triples,
the time required for the selection sort
will grow by a factor of nine. There will be three times
as many invocations, and each invocation requires three
times as much time, which means a factor of nine.
[Justify, in about 2 sentences.]
