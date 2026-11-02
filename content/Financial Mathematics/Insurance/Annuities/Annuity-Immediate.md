Annuity-immediate is a type of [[Annuity]] where payments occur at the end of each payment period. Not to be confused with [[Annuity-Due]] where payments occur at the beginning of each payment period.

## Present Value of Annuity-Immediate
The [[Present Value]] of an annuity-immediate is the value right now assuming no payments have been made. If we treated this annuity like a [[Bond]], how much would we sell it for? For an annuity with $n$ time periods and an [[Effective Interest Rate]] of $i$, we have the present value of the annuity as 
$$ a_{ni} = \nu + \nu^2 + \ldots + \nu^n = \frac{1-\nu^n}{i} $$
This equation stems from the [[Geometric Sequence]] formula when $c=r=\nu$.

For the accumulated value of an annuity-immediate at the end of its life span, we denote this with $s_{ni}$.

IMPORTANT NOTE
In general, the notation for annuity-immediate either for present value before any payments or final accumulated value, the notation is $a_n$ and $s_n$ respectively. Only when the [[Accumulation Function]] $a(t) = (1+i)^t$ do we use the notation $a_{\overline{n}\rceil  i}$ and $s_{ni}$.

$$\begin{matrix} \text{PAYMENT:} & & 1 & 1 & 1 & \ldots & 1 \\
\text{TIME:} & 0 & 1 & 2 & 3 & \ldots & n \\
\text{VALUE:} & a_n & & & & & s_n
\end{matrix}$$
 
$a_{\overline{n}\rceil}$ 