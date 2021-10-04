
# Sequences and Series
## Definitions
**Sequence**: *A finite or infinite list of numbers or functions.*
A sequence can be defined by a *general term*.
> $z[k]=(\displaystyle\frac{1}{4})^{k-1}$

**Series**: *The addition of the terms of a sequence.*
> $\displaystyle\sum_{k=0}^{\infty}z[k]=\displaystyle\sum_{k=0}^{\infty}(\frac{1}{4})^{k-1}$

**Arithmetic** sequence: *A sequence with a common difference between terms.*
They take the form $z[k]=a+(k-1)d$.

**Geometric** sequence: *A sequence with a common ratio, or multiple, between terms.*
They take the form $z[k]=ar^{(k-1)}$.

**Partial sum** $S_{n}$: *The sum of the first $n$ terms of an infinite sequence / series.*
For *arithmetic* sequences: $S_{n}=\displaystyle\frac{n}{2}[2a+(n-1)d]$
For *geometric* sequences: $S_{n}=\displaystyle\frac{a(1-r^{n})}{1-r}$ where $r \neq 1$

## Convergence and Divergence
A sequence **converges** if it approaches a finite value as $k$ approaches $\infty$. If not, it **diverges**.
>$z[k]=\frac{1}{k}$
$\displaystyle\lim_{k\to\infty}z[k]=0$ by inspection $\therefore$ $z[k]$ is *convergent*.

More examples:
>$x[k]=\sqrt{3+\frac{1}{k}}$
$\displaystyle\lim_{k\to\infty}x[k]=\sqrt{3+0}=\sqrt{3}\therefore$ *convergent*.

>$x[k]=(k+1)^2$
$\displaystyle\lim_{k\to\infty}x[k]=\infty\therefore$ *divergent*.

>$x[k]=\displaystyle\frac{2k^2+3k-1}{7k^2+4k+2}=\displaystyle\frac{2+\frac{3}{k}-\frac{1}{k^2}}{7+\frac{4}{k}+\frac{2}{k^2}}$
$\displaystyle\lim_{k\to\infty}x[k]=\frac{2}{7}\therefore$ *convergent*.

## Convergence of infinite series
A series will converge if the sequence of it's partial sums converges.
>Consider $\displaystyle\sum_{k=1}^{\infty}(\displaystyle\frac{1}{k}-\displaystyle\frac{1}{k+1})$
Take $\displaystyle\lim_{n\to\infty}S_n$ [where $S_n=\displaystyle\sum_{k=1}^{n}(\displaystyle\frac{1}{k}-\displaystyle\frac{1}{k+1})]$: 
$=\displaystyle\lim_{n\to\infty}S_n=\displaystyle\lim_{n\to\infty}[(\displaystyle\frac{1}{1}-\displaystyle\frac{1}{2})+(\displaystyle\frac{1}{2}-\displaystyle\frac{1}{3})+...+(\displaystyle\frac{1}{n}-\displaystyle\frac{1}{n+1})]$
$=\displaystyle\lim_{n\to\infty}(1-\displaystyle\frac{1}{n+1})\to1-0=1\therefore$ convergent.

As a rule of thumb:
- *Arithmetic* series will always diverge.
- *Geometric* series converge only if $|r|<1.$
>For convergent geometric series:
$\displaystyle\lim_{n\to\infty}S_n=\displaystyle\lim_{n\to\infty}\frac{a(1-r^n)}{1-r}=\frac{a(1-0)}{1-r}=\frac{a}{1-r}$ which is finite.

## Convergence tests
You cannot always tell convergence for general series with inspection. There are various tests available for these series. These tests only work for series of positive terms.
**Comparison test**: A series is *convergent* if each of it's terms are *smaller than or equal to* the corresponding terms of another convergent series of positive terms.
**Ratio test**: For a series $\displaystyle\sum_{k=1}^{\infty}a_k$:
It is *convergent* if $\displaystyle\lim_{k\to\infty}(\displaystyle\frac{a_{k+1}}{a_k})<1$, and *divergent* if $\displaystyle\lim_{k\to\infty}(\displaystyle\frac{a_{k+1}}{a_k})>1$.
