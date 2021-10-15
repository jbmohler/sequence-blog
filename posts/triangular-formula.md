# Our first sequence (revisited)

In our first post, we discussed the triangular numbers.  They are defined by 
$$
a_n=1+2+...+n.
$$

It so happens that there is a simple formula for computing $a_n$.  It is 
$$
a_n=\frac{n(n+1)}{2}.
$$

How do we know this formula is accurate?  Carl Friedrich Gauss is alleged to
have discovered this formula as a young lad when his teacher set a punishment
of adding the numbers from 1 to 100.  Young Gauss saw that you could pair
numbers from the opposite ends:
$$
101=1+100
$$
$$
101=2+99
$$
and so on.  The desired sum was then $101*50$ or $\frac{100(100+1)}{2}$.

# Proof by Induction

As cute as Gauss' proof of this formula is, there is a powerful mathematical
proof technique known as 'proof by induction' that can also be used here.
First we verify that our formula holds for $a_1$.  Then we show that *if* the
formula holds for $a_n$ it must be that the formula also holds for $a_{n+1}$.

Verify the formula for $a_1$:
$$
a_1=\frac{1(1+1)}{2}.
$$
As is typical of induction, this is obvious, $a_1=1$ and the fraction on the
right hand side is also $1$.

Now, we will show that if $a_n=\frac{n(n+1)}{2}$ then
$a_{n+1}=\frac{(n+1)(n+2)}{2}$ and the induction will be complete.  Very
briefly, the crux of the matter is
$$
\frac{n(n+1)}{2}+(n+1)=\frac{n(n+1)+2(n+1)}{2}=\frac{(n+2)(n+1)}{2}.
$$
The left hand side is $a_{n+1}=a_n+(n+1)$ and the right hand side is exactly
the expected formula for $a_{n+1}$.

Proof by induction will be just the thing for a few other items coming soon.
