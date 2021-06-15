---
usemathjax: true
---

To add two integers (in any [[Base]] expansion) we start with rightmost values
$$a_0 + b_0 = c_0 \cdot b + s_0$$

$s_0$ will be the rightmost bit of sum and $c_0$ will be the *carry*. Carry will be added to sum of next values.
$$a_1 + b_1 + c_0 = c_1 \cdot b + s_1$$

This process will go on till all the values are added.

[[Time Complexity]] of addition algorithm is $O(2n)$ (or simply $O(n)$) \[ $n$ times  addition of values + $n$ times addition of carries \].