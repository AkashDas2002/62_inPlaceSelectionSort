# 62_inPlaceSelectionSort

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
will grow by on average 3 times. With n elements, in the n-1 times the reigning champ is invoked, there are n-1 comparisons in the first one, n-2 comparisons in the second one, and so on. With 3n elements, there are 3n-1 invocations, and there are 3n-1 in the first one, 3n-2 in the second one, and so on. 
[Justify, in about 2 sentences.]

1. If the number of the elements in the input triples,
the number of times that the reigning champ algorithm
will be invoked 
will grow by (approximately) 3 times. When there are n elements, there are n-1 iterations,
and thus n-1 invocations of the algorithm. Likewise, when there are 3n elements, there are 3n-1 iterations, and thus 3n-1 invocations, which is about 3 times more than n-1.
[Justify, in about 2 sentences.]

2. If the number of the elements in the input triples,
the time required for the selection sort
will grow by about 9 times, since the number of invocations of reigning champ is tripled and the time it takes to execute each one is also tripled. Thus, the increase is around 3*3=9 times.
[Justify, in about 2 sentences.]
