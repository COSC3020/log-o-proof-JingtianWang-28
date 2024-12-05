# Asymptotic Equivalences

In the lectures, we said that logarithms with different bases don't affect the
asymptotic complexity of an algorithm. Prove that $O(\log_{2} n)$ is the same as
$O(\log_{5} n)$. Use the mathematical definition of $O$ -- do a formal proof,
not just the intuition.

I have started with the formal definition of $O$ below. Add your answer to this
markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$T(n) \in O(f(n)) \iff \exists c, n_0: T(n) \leq c \cdot f(n) \forall n \geq n_0$

///
$for f(n) = log_2(n)$

$∃c,n0: T(n) =< c*log_2 n(for all n>n0)$

$T(n) =< c*(log_5 n)/(log_5 2) $

$T(n) =< (1)/(log_5 2)c*log_5 n$


$for f(n) = log_5 n$

$∃c,n0: T(n) =< c*log_5 n(for all n>n0)$

$T(n) =< c*(log_2 n)/(log_2 5) $

$T(n) =< (1)/(log_2 5)c*log_2 n$

O(log_2 n) = O(log_5 n),so different base of log do not affect the asymptotic complexity of the algorithm
