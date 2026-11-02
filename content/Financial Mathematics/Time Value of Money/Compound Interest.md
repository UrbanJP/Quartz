Compound interest is a form of [[Interest]] where the interest is compounded. This means that after each crediting period, the new principal for the next interest calculation includes the old principal and interest of the current calculation. It can be thought of as reinvesting everything you earn.

There are three fairly common formulas to represent compound interest because different fields or problems utilize a different formula that may be easier for their needs. But for someone learning this lack of uniformity can cause confusion. Let's analyze the three formulas.
$$\begin{align}1.) \quad T &= P \times (1 + \frac{r}{n})^{nt}  \\ \\
2.) \quad T &= P \times(1 + \frac{i}{n})^n \\ \\
3.) \quad T &= P \times (1 + i)^t 
\end{align}$$
$P$ is the same for all formulas. It represents the [[Principal]]. 

For formula $1.)$, $r$ is the [[Nominal Interest Rate|Nominal Annual Rate]] (the rate before considering compounding), $n$ is the compounding periods __per year__, and $t$ is the number of years. 
For formula $2.)$, $i$ is used instead of $r$ but they represent the same thing, nominal annual interest rate, but $n$ is total __lifetime__ periods rather than periods per year. **This formula assumes only one year is under consideration. It does not work for any other time period.**
For formula $3.)$, $i=\frac{r}{n}$ from the first formula. Sometimes you may see $n$ instead of $t$ to represent time. I chose to use $t$ as it makes more sense with the previous formulas, but like the second formula, the compounding time period has to be **annual**, i.e., $n=1$.

My personal suggestion is to prioritize the first formula over the other two.

For different interest rates the same we can the formalization (of formula $3.)$) becomes $$T = P \times (1 + i_1)(1 + i_2) \ldots (1 + i_n)$$
where $i_k$ is the interest rate for the $k^{th}$ year.



### Examples
1.) Simple Compound Interest
Smith opens an account with $1000 and a savings account with 4% credited annually. How much will Smith have after five years?
- Answer: $1000 \times (1.04)^5 = 1216.65$  

2.) Compound Interest with transactions
Jones deposits $1000 into an account on January 1, 2000. The account credits interest at an annual [[Effective Interest Rate]] of 5% every December 31. Jones withdraws $200 on January 1, 2002, deposits $100 on January 1, 2003, and withdraws $250 on January 1, 2005. What is the balance on December 31, 2006?
- Answer: We can evaluate each transaction one at a time. This leads us to the following: $1000(1.05)^2 = 1102.50$  on December 31, 2001
  $1102.50 - 200 = 902.50$ on January 1, 2002 
  $902.50(1.05) = 947.63$ on December 31, 2002
  $947.63 + 100 = 1047.63$ on January 1, 2003
  $1047.63(1.05)^2 = 1155.01$ on December 31, 2004
  $115.01 - 250 = 905.01$ on January 1, 2005
  $905.01(1.05)^{2} = 997.77$ on December 31, 2006
  
  There is an alternative approach to this problem which is to write the whole thing as one equation,
  $$(((((1000(1.05)^2 - 200) \times 1.05) + 100) \times 1.05^2) - 250) \times 1.05^2 = 997.77$$
  but this equation can be simplified through distribution
  $$1000(1.05)^7 - 200(1.05)^5 + 100(1.05)^4 - 250(1.05)^2 = 977.77$$
 
 