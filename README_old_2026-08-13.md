# The Statistical Price of Direction in Learning Conditional Averages

## Abstract

Learning conditional averages asks for the average binary label in the neighborhood of every test point. A recent combinatorial characterization proves learnability on arbitrary directed neighborhood graphs, but its quantitative lower and upper bounds differ by logarithmic factors. We determine the exact minimax rates and expose an unexpected critical phenomenon. Let $d$ be the largest shattered independent set and let $k$ be the largest bichromatic independent set, the two parameters in the characterization. Under the power loss $|\widehat s-s|^p$ and any fixed confidence, the optimal sample complexity on directed graphs is

$$\Theta_p\\\\\\!\left(\frac d\varepsilon+
\begin{cases}
k\varepsilon^{-2/p},&0<p<2,\\\\
k\varepsilon^{-1}\log(1/\varepsilon),&p=2,\\\\
k\varepsilon^{-1},&p>2.
\end{cases}\right).$$

On undirected graphs the logarithm at $p=2$ disappears, while every other graph-class minimax rate is unchanged. Thus square loss is the unique exponent at which direction changes the worst-case order characterized by $(d,k)$. The upper bounds follow from a sharp occupancy functional. Directed light-neighborhood inequalities produce a harmonic sum only at the critical exponent, while a weighted Caro-Wei argument collapses all scales in the undirected case. For the converse, a fixed countable transitive tournament with geometrically weighted opposite-label pairs carries one hard parameter at every resolvable scale. Each scale contributes order $1/m$ squared risk even though the graph has independence number one. Disjoint unions give the full $k\log(m/k)/m$ lower bound. The construction uses a known singleton concept, so the logarithm is caused entirely by estimating the marginal distribution. The results close the quantitative gap for square loss and give a complete loss-dependent phase diagram for conditional-average learning.

## Contributions

Our results provide: (i) exact expected-risk and constant-confidence minimax rates for every fixed power $p>0$, (ii) the first matching square-loss lower bound for the conditional-average characterization, improving the previous $k/(\varepsilon\log k)$ term to $k\log(1/\varepsilon)/\varepsilon$, (iii) an exact directed-versus-undirected separation, and (iv) an occupancy principle that isolates the interaction between graph orientation, neighborhood mass, and loss curvature. The lower bounds hold for a known singleton concept. They are distribution-estimation barriers rather than classification barriers.

## Keywords

statistical, price, direction, learning, conditional, averages, asks, average, binary

## Files

- `main.pdf`
- `main.tex`
- `references.bib`
- `iclr2027_conference.sty`, `iclr2027_conference.bst`, `natbib.sty`, `fancyhdr.sty`
- `main.pdf.ots`, `README.md.ots` OpenTimestamps priority proofs
