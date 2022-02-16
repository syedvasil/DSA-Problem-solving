<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    awesee <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/awesee                                 |-->
<!--|@home      https://github.com/awesee/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](../the-number-of-passengers-in-each-bus-i "The Number of Passengers in Each Bus I")
　　　　　　　　　　　　　　　　
[Next >](../minimum-cost-of-buying-candies-with-discount "Minimum Cost of Buying Candies With Discount")

## [2143. Choose Numbers From Two Arrays in Range (Hard)](https://leetcode.com/problems/choose-numbers-from-two-arrays-in-range "")



### Related Topics
  [[Array](../../tag/array/README.md)]
  [[Dynamic Programming](../../tag/dynamic-programming/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
If you know the possible sums you can get for a range [l, r], how can you use this information to calculate the possible sums you can get for a range [l, r + 1]?
</details>

<details>
<summary>Hint 2</summary>
For the range [l, r], if it is possible to choose elements such that the sum of elements you picked from nums1 is x and the sum of elements you picked from nums2 is y, then (x + nums1[r + 1], y) and (x, y + nums2[r + 1]) are possible sums you can get in the range [l, r + 1].
</details>

<details>
<summary>Hint 3</summary>
How can we save the possible sums obtainable at a given index so that we can reuse this information later?
</details>