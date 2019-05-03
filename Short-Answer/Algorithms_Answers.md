### Runtime Complexity

a. O(n)

- while it doesn't run one operation per increase in n, it does have a linear runtime.
  b. O(n^3)
- the first three loops have a runtime of n each, the last loop only runs 10 times regardless of input size. When simplifying the runtime, you drop the 10.
  c. O(n)
- the recursive function runs and decrements towards zero. It has a linear runtime

### Exercise II

I would approach this problem by taking a similar approach to binary search. If I am searching for a single floor, I can start at the center of the array, eliminate the top or bottom half depending on the egg breaking or not. I can continue this process halving the floors with each drop until I have found the solution. This would have a runtime of O(log(n)).
