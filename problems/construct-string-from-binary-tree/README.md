<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    Openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

## 606. Construct String from Binary Tree (Easy)

<p>You need to construct a string consists of parenthesis and integers from a binary tree with the preorder traversing way.</p>

<p>The null node needs to be represented by empty parenthesis pair "()". And you need to omit all the empty parenthesis pairs that don't affect the one-to-one mapping relationship between the string and the original binary tree.</p>

<p><b>Example 1:</b><br />
<pre>
<b>Input:</b> Binary tree: [1,2,3,4]
       1
     /   \
    2     3
   /    
  4     

<b>Output:</b> "1(2(4))(3)"
<br/><b>Explanation:</b> Originallay it needs to be "1(2(4)())(3()())", <br/>but you need to omit all the unnecessary empty parenthesis pairs. <br/>And it will be "1(2(4))(3)".
</pre>
</p>

<p><b>Example 2:</b><br />
<pre>
<b>Input:</b> Binary tree: [1,2,3,null,4]
       1
     /   \
    2     3
     \  
      4 

<b>Output:</b> "1(2()(4))(3)"
<br/><b>Explanation:</b> Almost the same as the first example, <br/>except we can't omit the first parenthesis pair to break the one-to-one mapping relationship between the input and the output.
</pre>
</p>

### Related Topics
[[Tree](https://github.com/openset/leetcode/tree/master/tag/tree/README.md)]
[[String](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]

### Similar Questions
  1. [Construct Binary Tree from String](https://github.com/openset/leetcode/tree/master/problems/construct-binary-tree-from-string) (Medium)
  1. [Find Duplicate Subtrees](https://github.com/openset/leetcode/tree/master/problems/find-duplicate-subtrees) (Medium)