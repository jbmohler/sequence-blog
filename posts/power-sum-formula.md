---
title: Generalized Power Sums
---
## Correction Corner

The triangular array of numbers from last post is "pascal's" triangle, not
"bernoulli's" triangle.  However they are very closely related.

## A computational interlude

We showed a formula for the sum of the first $n$ cubes.  Here's a much more
general collection of formulas.  Side note is that the only place I've seen
these used beyond the sum of the triangular numbers is in Calc II when manually
computing integrals of polynomials before we've learned anti-differentation
power rule.

$$
\sum_{i=1}^ni^0=n
$$
$$
\sum_{i=1}^ni^1=\frac{n \left(n + 1\right)}{2}
$$
$$
\sum_{i=1}^ni^2=\frac{n \left(n + 1\right) \left(2 n + 1\right)}{6}
$$
$$
\sum_{i=1}^ni^3=\frac{n^{2} \left(n + 1\right)^{2}}{4}
$$
$$
\sum_{i=1}^ni^4=\frac{n \left(n + 1\right) \left(2 n + 1\right) \left(3 n^{2} + 3 n - 1\right)}{30}
$$
$$
\sum_{i=1}^ni^5=\frac{n^{2} \left(n + 1\right)^{2} \left(2 n^{2} + 2 n - 1\right)}{12}
$$
$$
\sum_{i=1}^ni^6=\frac{n \left(n + 1\right) \left(2 n + 1\right) \left(3 n^{4} +
6 n^{3} - 3 n + 1\right)}{42}
$$
$$
\sum_{i=1}^ni^7=\frac{n^{2} \left(n + 1\right)^{2} \left(3 n^{4} + 6 n^{3} -
n^{2} - 4 n + 2\right)}{24}
$$
$$
\sum_{i=1}^ni^8=\frac{n \left(n + 1\right) \left(2 n + 1\right) \left(5 n^{6} +
15 n^{5} + 5 n^{4} - 15 n^{3} - n^{2} + 9 n - 3\right)}{90}
$$
$$
\sum_{i=1}^ni^9=\frac{n^{2} \left(n + 1\right)^{2} \left(n^{2} + n - 1\right)
\left(2 n^{4} + 4 n^{3} - n^{2} - 3 n + 3\right)}{20}
$$
$$
\sum_{i=1}^ni^{10}=\frac{n \left(n + 1\right) \left(2 n + 1\right) \left(n^{2} +
n - 1\right) \left(3 n^{6} + 9 n^{5} + 2 n^{4} - 11 n^{3} + 3 n^{2} + 10 n -
5\right)}{66}
$$
$$
\sum_{i=1}^ni^{11}=\frac{n^{2} \left(n + 1\right)^{2} \left(2 n^{8} + 8 n^{7} + 4
n^{6} - 16 n^{5} - 5 n^{4} + 26 n^{3} - 3 n^{2} - 20 n + 10\right)}{24}
$$
$$
\sum_{i=1}^ni^{12}=\frac{n \left(n + 1\right) \left(2 n + 1\right) \left(105
n^{10} + 525 n^{9} + 525 n^{8} - 1050 n^{7} - 1190 n^{6} + 2310 n^{5} + 1420
n^{4} - 3285 n^{3} - 287 n^{2} + 2073 n - 691\right)}{2730}
$$
$$
\sum_{i=1}^ni^{13}=\frac{n^{2} \left(n + 1\right)^{2} \left(30 n^{10} + 150 n^{9}
+ 125 n^{8} - 400 n^{7} - 326 n^{6} + 1052 n^{5} + 367 n^{4} - 1786 n^{3} + 202
n^{2} + 1382 n - 691\right)}{420}
$$
$$
\sum_{i=1}^ni^{14}=\frac{n \left(n + 1\right) \left(2 n + 1\right) \left(3 n^{12}
+ 18 n^{11} + 24 n^{10} - 45 n^{9} - 81 n^{8} + 144 n^{7} + 182 n^{6} - 345
n^{5} - 217 n^{4} + 498 n^{3} + 44 n^{2} - 315 n + 105\right)}{90}
$$
