# Sequences and Series
## Definitions
**Sequence**: *A finite or infinite list of numbers or functions.*
A sequence can be defined by a *general term*.
eg. $z[k]=(\frac{1}{4})^{k-1}$

**Series**: *The addition of the terms of a sequence.*
eg. $\displaystyle\sum_{k=0}^{\infty}z[k]=\displaystyle\sum_{k=0}^{\infty}(\frac{1}{4})^{k-1}$

**Arithmetic** sequence: *A sequence with a common difference between terms.*
They take the form $z[k]=a+(k-1)d$.

**Geometric** sequence: *A sequence with a common ratio, or multiple, between terms.*
They take the form $z[k]=ar^{(k-1)}$.

**Partial sum** $S_{n}$: *The sum of the first $n$ terms of an infinite sequence / series.*
For *arithmetic* sequences: $S_{n}=\frac{n}{2}[2a+(n-1)d]$
For *geometric* sequences: $S_{n}=\frac{a(1-r^{n})}{1-r}$ where $r \neq 1$

## Convergence and Divergence
A sequence **converges** if it approaches a finite value as $k$ approaches $\infty$. If not, it **diverges**.
eg. $z[k]=\frac{1}{k}$
$\displaystyle\lim_{k\to\infty}z[k]=0$ by inspection $\therefore$ $z[k]$ is *convergent*.

Examples:
1. $x[k]=\sqrt{3+\frac{1}{k}}$
$\displaystyle\lim_{k\to\infty}x[k]=\sqrt{3+0}=\sqrt{3}\therefore$ *convergent*.

2. $x[k]=(k+1)^2$
$\displaystyle\lim_{k\to\infty}x[k]=\infty\therefore$ *divergent*.

3. $x[k]=\frac{2k^2+3k-1}{7k^2+4k+2}=\frac{2+\frac{3}{k}-\frac{1}{k^2}}{7+\frac{4}{k}+\frac{2}{k^2}}$
$\displaystyle\lim_{k\to\infty}x[k]=\frac{2}{7}\therefore$ *convergent*.

## Convergence of series
