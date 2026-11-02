Force of interest is the instantaneous rate of growth of the [[Accumulation Function]] relative to the current value of the accumulation function. For a [[Nominal Interest Rate]] $i^{(m)}$, the force of interest is the [[Limit]] as $m$ goes to [[Infinity]] of $i^{(m)}$. In general, force of interest is equal to
$$\delta_t = \frac{a'(t)}{a(t)} = \frac{d}{dt} \ln a(t)$$
For the nominal interest rate we get 
$$ \delta = \lim_{m \to \infty}i^{(m)} = \ln (1+i)$$
The above is derived from the solving for $i^{(m)}$ in the equation 
$$\begin{align} i &= \left(1 + \frac{i^{(m)}}{m} \right)^{m} \, - 1 \\ \\
i^{(m)} &= m((i+1)^{1/m} -1) \\ \\
&= \frac{(i+1)^{1/m} -1}{1/m}
\end{align}$$
Then we can apply a limit and apply [[L'Hopital's Rule]] utilizing a derivative with respect to $m$
$$\begin{align} \lim_{m \to \infty} i^{(m)} &= \frac{(-m^{-2})\ln(i +1)(i+1)^{1/m}}{-m^{-2}} \\ \\ 
&= \ln(i +1)(i+1)^{1/m} \\ \\
\delta &= \ln(i+1)
\end{align} $$


Consider the [[Effective Interest Rate]] between a time $t$ and $t+1$. This would turn out to be $\frac{a(t+1)-a(t)}{a(t)}$where $a(t)$ is the [[Accumulation Function]]. Using this same formula we can substitute $1$ for a smaller time $\frac{1}{m}$ resulting in an effective rate of $\frac{a(t+\frac{1}{m}) -a(t)}{a(t)}$. When translating this into a [[Nominal Interest Rate]] we divide by $\frac{1}{m}$ which is the same as multiplying by $m$. Taking the [[Limit]] of $m$ to $\infty$ we get the force of interest formula $$ \delta_t = \frac{a'(t)}{a(t)}$$


