An initial distribution, sometimes denoted as $\nu$ (Nu) or $\pi$ is the [[Probability Mass Function]] for the initial state $Y_0$ in a [[Markov Chain]]. If $\nu$ is the distribution, each state would be represented as $\nu_j$ and is defined as $$\nu_j = P(Y_0 = j)$$
where $Y_0$ is the [[Random Variable]] at time $t=0$. Considering all states $j$, $\sum_{j \in \mathbb{S}} \nu_j = 1$ making $\nu$ a valid pmf. The list of states for $\nu$ is listed as $\{ \nu_j | j \in \mathbb{S} \}$ where $\mathbb{S}$ is the [[State Space]] of the Markov chain. It's important to note that each $j$ is in $\mathbb{S}$ which is the state space, but $\mathbb{S}$ is also acting as an [[Index Set]] for defining each state $\nu_j$ in the distribution $\nu$.

You may see the following notation $\mathbb{P}_{\nu}(Y_n = k)$. This just means the probability of the random variable $Y_n$ equaling $k$ given our initial distribution is $\nu$. If $\nu$ is our initial distribution the values our initial random variable can take is every single $\nu_j$ in $\nu$. 

## Examples
Consider $\mathbb{S} = \{1,2,3 \}$. Then $\{ \nu_j | j \in \mathbb{S} \} = \{ \nu_1, \nu_2, \nu_3 \}$. We can have our initial random variable $Y_0$ equal to any of these three. So to calculate the probability $Y_n = k$ given the entire initial distribution $\nu$ we have that
$$\mathbb{P}_{\nu}(Y_n = k) = \sum_{j \in \mathbb{S}} \mathbb{P}(Y_0 = j) \mathbb{P}(Y_n = k | Y_0 = j) = \sum_{j \in \mathbb{S}} \nu_j p_{jk}^{(n)}$$
where $p_{jk}^{(n)}$ is the $(j,k)$ element of the $n$-step [[Transition Matrix]] $P^{(n)}$.
- As a quick note on the above example, why does the summation include $\mathbb{P}(Y_0 = j)$ instead of just being $\mathbb{P}(Y_n = k | Y_0 = j)$? Consider an example where  $\mathbb{P}(Y_n = k | Y_0 = j)=1$ but $\mathbb{P}(Y_0 = j)=0$. Then intuitively $\mathbb{P}_{\nu}(Y_n = k)$ would also be zero. This is why both components are included.

A special case $\mathbb{P}_j$ is where $\nu_j = 1$ and all other states $\nu_{a}=0$ where $a \in \mathbb{S}$ and $a \neq j$.