---
title: Cube Partial Sums
---

# A Formula for the Sums of the First $n$ Cubes

This post will show by induction that the sum of the first $n$ cubes is given
by 
$$
1+8+...+n^3=\frac{n^2(n+1)^2}{4}.
$$
Remember that there are 2 steps to a proof by induction, the first is
(generally) easy to show the base case.  That is 
$$
1=\frac{1^2(1+1)^2}{4}.
$$
That is so easy and silly looking that I worry it belies the actual point :(.

To complete the proof, we add $(n+1)^3$ to $\frac{n^2(n+1)^2}{4}$ and show that
the sum can be expressed in the same form with $n$ replaced by $n+1$.
$$
\frac{n^2(n+1)^2}{4}+(n+1)^3=\frac{n^2(n+1)^2}{4}+\frac{4(n^3+3n^2+3n+1)}{4} \\
=\frac{n^2(n+1)^2}{4}+\frac{4(n^3+2n^2+n)+4(n^2+2n+1)}{4} \\
=\frac{n^2(n+1)^2}{4}+\frac{4n(n^2+2n+1)+4(n^2+2n+1)}{4} \\
=\frac{n^2(n+1)^2}{4}+\frac{4n(n+1)^2+4(n+1)^2}{4} \\
=\frac{(n^2+4n+4)(n+1)^2}{4} \\
=\frac{(n+2)^2(n+1)^2}{4}.
$$
This completes the proof by induction.

# Triangular Numbers Again!

Remember that the triangular numbers $1+2+3+...+n=T_n$ could be expressed as 
$$
T_n=\frac{n(n+1)}{2}.
$$
This is exactly the square root of the sum of the first $n$ cubes as given above.

Two posts back, we computed the first several sums of cubes as $1, 9, 36, 100,
...$ and observed that they are perfect squares.  In fact, they are squares of
triangular numbers!
