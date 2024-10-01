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
$log_2 (n) = (log_5 (n))/ (log_5 (2))$
$log_5 (n) = (log_2 (n))/ (log_2 (5))$
so those two have a multiple relationship
by the def of big o, T(n)<= c for all n >= n0
$log_2 (n) =< c log_5 (n), for all n>= n0
$log_2 (n) ∈ O log_5 (n)$
$because $log_5 (n) = (log_2 (n))/ (log_2 (5))$
$so 1/(log_5 (n))* (log_2 (n)) = (log_5 (n))%
$O log_2 (n) = c O log_5 (n)$
$(log_5 (n)) ∈  (log_2 (n))$
