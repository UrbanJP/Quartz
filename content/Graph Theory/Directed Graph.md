A directed graph is a graph consisting of points called [[Node|Nodes]] and their connections called [[Edge (Graph Theory)|Edges]]. The connection between [[Node|Nodes]] have a direction. They have an orientation such as from node $A$ to node $B$. the connection from $B$ to $A$ requires a separate edge.


## Examples
Consider a [[Markov Chain]] with the following [[Transition Matrix]]:
$$ P = \begin{matrix} a\\ b\\ c\\ d\\ e\\ \end{matrix}
\begin{bmatrix} 0&0.2&0.3&0.5&0\\
0.3&0.2&0.1&0.1&0.3\\
0.9&0&0&0&0.1\\
0.2&0.4&0.2&0.1&0.1\\
0&0.2&0.3&0.3&0.2\\
\end{bmatrix}$$

Then the directed ([[Weighted Directed Graph|Unweighted]]) graph would be 

```tikz
\begin{tikzpicture}[
  vertex/.style={draw, circle, minimum size=8mm},
  weight/.style={font=\small, fill=white, inner sep=1pt}
]
  \node[vertex] (a) at (0,0) {A};
  \node[vertex] (b) at (3,0) {B};
  \node[vertex] (c) at (1.5,2) {C};
  \node[vertex] (d) at (4.5,2) {D};

  \draw (a) -- node[weight, below] {5} (b);
  \draw (a) -- node[weight, left] {3} (c);
  \draw (b) -- node[weight, right] {2} (c);
  \draw (b) -- node[weight, below right] {4} (d);
  \draw (c) -- node[weight, above] {1} (d);
\end{tikzpicture}
```

