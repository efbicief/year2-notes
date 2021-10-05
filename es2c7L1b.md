# Binomial and Taylor / Maclaurin series
## Binomial theorem
The binomial theorem can be used to expand expressions in the form $(a+b)^n$. \
When n is a positive integer:
> $(a+b)^n=a^n+na^{n+1}b+\displaystyle\frac{n(n-1)}{2!}a^{n-2}b^2+...+b^n$ \
> $(a+b)^n=a^n(1+\displaystyle\frac{b}{a})^n$

If n is not a positive integer, but $-1<x<1$:
> $(1+x)^n=1+nx+\displaystyle\frac{n(n-1)}{2!}x^2+...+\displaystyle\frac{n(n-1)...(n-r+1)}{r!}x^r$ 

Note that in this case an infinite converging series is generated.
## Taylor and Maclaurin series
Suppose a function $f(x)$ can be expressed as an infinite power (polynomial) series, $f(x)$ is continually differenciable, and it's derivatives are known at a point $x=a$. Then:
> $f(x)=\displaystyle\sum_{n=0}^{\infty}\displaystyle\frac{1}{n!}f^{(n)}(a)(x-a)^n$ where $f^{(n)}$ is the nth differencial of $f$.

### Using the Taylor series
> Suppose $f(x)$ is of the form $\displaystyle\sum_{n=0}^{\infty}c_n(x-a)^n$ \
> $=c_0+c_1(x-a)+c_2(x-a)^2+...+c_n(x-a)^n$.
> 
We can find coefficients $c_n$ by differenciating.
> Let $x=a$ , $f(x)=f(a)=\displaystyle\sum_{n=0}^{\infty}c_n(0)^n=c_0$ \
> $f(a)=c_0$.
> 
Continuing to differenciate and letting $x=a$ yields: 
> $c_1=f'(a), c_2=\displaystyle\frac{1}{2}f''(a),c_3=\displaystyle\frac{1}{6}f'''(a), ...$ 
> 
This can be generalised as:
> $c_n=\displaystyle\frac{1}{n!}f^{(n)}(a)$

Substituting back into $f(x)$ yields:
> $f(x)=\displaystyle\sum_{n=0}^{\infty}\displaystyle\frac{1}{n!}f^{(n)}(a)(x-a)^n$

### Maclaurin series
The Maclaurin series is just the Taylor series approximated around $x=0$, i.e. $a=0$.
> $f(x)=\displaystyle\sum_{n=0}^{\infty}\frac{1}{n!}f^{(n)}(0)x^n$