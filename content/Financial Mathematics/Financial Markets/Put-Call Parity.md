Put-Call parity shows how European [[Option|Options]] can yield the same value for any market price $S_T$. At time $T$, a call option plus cash that is worth $K$ at time $T$ is equal to a put option plus a stock valued at market price. 

Consider two conditions: $S_T >K$ and $S_T < K$ where $S_T$ represents [[Market]] price at time $T$ and $K$ represents the [[Strike Price]] of the option.


$S_T > K$ .......................
$$\begin{matrix} \text{European Call Option + Cash} & \text{European Put Option + Stock} \\
\text{max}(S_T - K, 0) + K & \text{max}(K-S_{T},0) + S_{T} \\ S_{T} - K +K & \\ S_{T} & S_{T} \end{matrix}$$

$S_{T}<K$
- Euro