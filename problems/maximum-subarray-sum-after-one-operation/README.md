<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](../palindrome-partitioning-iv "Palindrome Partitioning IV")
　　　　　　　　　　　　　　　　
[Next >](../leetflex-banned-accounts "Leetflex Banned Accounts")

## [1746. Maximum Subarray Sum After One Operation (Medium)](https://leetcode.com/problems/maximum-subarray-sum-after-one-operation "")



### Related Topics
  [[Dynamic Programming](../../tag/dynamic-programming/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
Think about dynamic programming
</details>

<details>
<summary>Hint 2</summary>
Define an array dp[nums.length][2], where dp[i][0] is the max subarray sum including nums[i] and without squaring any element.
</details>

<details>
<summary>Hint 3</summary>
dp[i][1] is the max subarray sum including nums[i] and having only one element squared.
</details>