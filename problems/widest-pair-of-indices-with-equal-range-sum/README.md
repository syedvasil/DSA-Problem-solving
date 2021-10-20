<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](../find-array-given-subset-sums "Find Array Given Subset Sums")
　　　　　　　　　　　　　　　　
[Next >](../minimum-difference-between-highest-and-lowest-of-k-scores "Minimum Difference Between Highest and Lowest of K Scores")

## [1983. Widest Pair of Indices With Equal Range Sum (Medium)](https://leetcode.com/problems/widest-pair-of-indices-with-equal-range-sum "")



### Hints
<details>
<summary>Hint 1</summary>
Keep prefix sums of both arrays.
</details>

<details>
<summary>Hint 2</summary>
Can the difference between the prefix sums at an index help us?
</details>

<details>
<summary>Hint 3</summary>
What happens if the difference between the two prefix sums at an index a is x, and x again at a different index b?
</details>

<details>
<summary>Hint 4</summary>
This means that the sum of nums1 from index a + 1 to index b is equal to the sum of nums2 from index a + 1 to index b.
</details>