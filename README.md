# Laplace-Beltrami spectrum of the Aloff-Wallach space $W^{1,1}$

This repository contains the *Electronic Supplementary Material* for the paper:

> **The Laplace-Beltrami spectrum on naturally reductive homogeneous spaces**  
> *Ilka Agricola and Jonas Henkel*

It provides the source code for the explicit computation of the Laplace-Beltrami spectrum of the Aloff-Wallach space $W^{1,1}$, the corresponding plots, and consistency checks with known results.

## Recommended browser view

GitHub sometimes fails to render the Jupyter notebook file (`Agricola, Henkel Calculation Spectrum.ipynb`) in the web preview and shows only `An error occurred`. The following HTML version is provided as a stable browser-readable rendering with code cells and recorded outputs in notebook order:

- <a href="https://jmhenkel.github.io/Electronic-supplements/Agricola_Henkel_Calculation_Spectrum.html" target="_blank" rel="noopener noreferrer">Agricola_Henkel_Calculation_Spectrum.html</a>

The original executable notebook is also included:

- `Agricola, Henkel Calculation Spectrum.ipynb`

## Content

The Jupyter Notebook `Agricola, Henkel Calculation Spectrum.ipynb` covers the following topics:

1. **Explicit computation:** Computation of $\Sigma(W^{1,1}, g_{t_0,t_1})$.
2. **Plots:** Visualizations of $\Sigma(W^{1,1}, g_{t_0,t_1})$ for several parameter choices.
3. **Compatibility check:** Verification that multiplicities agree with the results of Urakawa.
4. **Basic eigenvalues:** Consistency check with the spectrum of $\mathbb{CP}^2$.

## Usage

To run the code, you need a working Python installation with `numpy`, `sympy`, and `matplotlib`.

1. Clone the repository:
   ```bash
   git clone https://github.com/jmhenkel/Electronic-supplements.git
   ```
2. Open the notebook `Agricola, Henkel Calculation Spectrum.ipynb` in Jupyter or VS Code.
3. Execute the cells.
