# On the Hausdorff Dimension and Falconer's Distance Conjecture

My undergraduate thesis in mathematics at AUC, completed in Summer 2025 under the supervision of Dr. Eslam Badr in partial fulfillment of the BSc in Mathematics.

## About

This thesis is primarily expository. I wrote it to teach myself the geometric measure theory and harmonic analysis surrounding Falconer's distance conjecture. The conjecture states that for a Borel set $A \subset \mathbb{R}^d$ with $d \geq 2$, if $\dim_H(A) > d/2$, then the Euclidean distance set $\Delta(A) = \{\|x - y\| : x, y \in A\}$ has positive Lebesgue measure. It remains open in all dimensions.

The thesis builds up the necessary machinery from the ground up:

- Hausdorff measure and dimension, with a worked computation for the generalized Cantor set
- Frostman's Lemma and the equivalence between Hausdorff dimension and finiteness of Riesz energy integrals
- Fourier transforms of measures, the Fourier representation of the $s$-energy, and Marstrand's projection theorem
- Falconer's 1986 partial result toward the conjecture
- A brief survey of recent progress (Bourgain, Wolff, Erdoğan, Guth–Iosevich–Ou–Wang, and the Du et al. line of work) via weighted Fourier restriction estimates

## Original contribution

My original work is a small generalization in §4.2. Falconer (1985) showed the conjecture fails when the Euclidean norm is replaced by the supremum norm, exhibiting a single counterexample $E \subset \mathbb{R}^2$ with $\dim_H(E) = 3/2$ and zero $L^\infty$-distance-set measure.

I extend this to a parametric family: for each integer $m \geq 3$, I construct a compact set $E_m \subset \mathbb{R}^2$ with

$$\dim_H(E_m) = \frac{2(m-1)}{m} \quad \text{and} \quad \mathcal{L}^1(\Delta'(E_m)) = 0,$$

where $\Delta'$ denotes the distance set under the supremum norm. Falconer's original example corresponds to $m = 4$. Since $\dim_H(E_m) \to 2$ as $m \to \infty$, the $L^\infty$ analogue of Falconer's conjecture fails not just near its critical threshold $d/2 = 1$, but at Hausdorff dimensions arbitrarily close to the ambient dimension. The proof also yields an explicit upper bound

$$\dim_H(\Delta'(E_m)) \leq \frac{m - 1 + \log_{10} 2}{m},$$

and the construction extends to $\mathbb{R}^d$ via $E_m^{(d)} = A^d$.

## Files
- `Thesis_HazemAjlan.pdf` — the thesis
- `main.tex` — LaTeX source
- `Bibliography.bib` — references
