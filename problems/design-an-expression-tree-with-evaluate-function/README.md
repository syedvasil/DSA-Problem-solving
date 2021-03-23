<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](../graph-connectivity-with-threshold "Graph Connectivity With Threshold")
　　　　　　　　　　　　　　　　
[Next >](../slowest-key "Slowest Key")

## [1628. Design an Expression Tree With Evaluate Function (Medium)](https://leetcode.com/problems/design-an-expression-tree-with-evaluate-function "设计带解析函数的表达式树")



### Related Topics
  [[Tree](../../tag/tree/README.md)]
  [[Design](../../tag/design/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
Apply the concept of Polymorphism to get a good design
</details>

<details>
<summary>Hint 2</summary>
Implement the Node class using NumericNode and OperatorNode classes.
</details>

<details>
<summary>Hint 3</summary>
NumericNode only maintains the value and evaluate returns this value.
</details>

<details>
<summary>Hint 4</summary>
OperatorNode Maintains the left and right nodes representing the left and right operands, and the evaluate function applies the operator to them.
</details>