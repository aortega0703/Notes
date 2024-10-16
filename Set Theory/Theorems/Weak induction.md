---
tags:
  - theorem
  - set_theory
related topics:
  - "[[Integers]]"
---
For a set $S$ and an integer $k\in S$, if $S$ has the property that $n+1 \in S$ whenever $n\in S$ then $n\in S$ for all $n\geq k$.
##### Proof:
Let $M=\{m + |k|: m > k, m\notin S\}$. As $m>k$ then $m+|k| > 0$ for all $m+|k|\in M$, then suppose $M$ is nonempty so by [[Well ordering principle]] it has a least element $m + |k|$. As $m$ is the least element not in $S$ then $m-1\in S$. However $m = (m-1) + 1 \in S$ which is a contradiction. Therefore $M$ is empty and $n\in S$ for all $n\geq k$.