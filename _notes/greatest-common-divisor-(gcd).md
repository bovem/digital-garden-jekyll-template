---
usemathjax: true
---

Let $a$ and $b$ be two integers such that $a, b \neq 0$.
Largest number $d$ such that $d | a$ and $d | b$ is *Greatest Common Divisor* of $a$ and $b$. It will be denoted as $gcd(a, b)$.

### Subtopics
- [[Relatively Prime]]
- [[Euclidean Algorithm]]
- [[Bézout Theorem]]

### Finding GCD using [[Prime Factorization]]

Given $a = p_1^{a_1}p_2^{a_2} \dots p_n^{a_n}$ and $b = p_1^{b_1}p_2^{b_2} \dots p_n^{b_n}$.

Then $gcd(a, b) = p_1^{min(a_1, b_1)}p_2^{min(a_2, b_2)} \dots p_n^{min(a_n, b_n)}$
