The Limiting probability of a state $k$ in a [[Markov Chain]] is the probability of being in state $k$ as time approaches infinity. This is regardless of any prior states including the initial starting position. This notion is related to the [[Limiting Distribution]] of the Markov chain.


## Formal Definition
Let $k$ be a fixed value in the [[State Space]] $\mathbb{S}$, we say that $k$ has limiting probability $\pi_k \in [0,1]$ if $$\forall j \in \mathbb{S}, \quad \lim_{n \to \infty} p_{jk}^{(n)} = \pi_k$$ where $p_{jk}^{(n)}$ is the $(j,k)$ element of the $n$-step [[Transition Matrix]] $P^{(n)}$.


## Examples
1. Sunny day and rainy day example