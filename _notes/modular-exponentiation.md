---
usemathjax: true
---

To find $b^n\ mod\ m$ efficiently we use [[Base]] expansion formula.

$$b^n = b^{a_{(k-1)}2^{(k-1)} + a_{(k-2)}2^{(k-2)} + \dots a_{1}2 + a_0} = b^{a_{(k-1)}2^{(k-1)}} b^{a_{(k-2)}2^{(k-2)}} \dots b^{a_1 2} b^{a_0}$$

We multiply $b^{2j}$ to each term where $a_j=1$ and take modulo $m$ for each of them.

[[Time Complexity]] of this algorithm is $O((log\ m)^2\ log\ n)$.