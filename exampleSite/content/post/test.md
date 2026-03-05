---
title: "Typography & Elements Test"
date: 2026-02-21T10:00:00Z
type: "post"
math: true
tags: ["Test", "Physics", "Design"]
summary: "This is a comprehensive test page to evaluate the typography, blockquotes, code blocks, and mathematical formulas in our new Metro-Material hybrid theme."
---

Welcome to the typography test page. This paragraph tests the standard body text. In physics, we often deal with concepts like **Quantum Entanglement** (bold text) and *Spontaneous Symmetry Breaking* (italic text). Sometimes we refer to a specific variable like `var_energy` (inline code).

## 1. Blockquotes (学术引用)

In academic writing, we often cite literature or emphasize core principles:

> "I think I can safely say that nobody understands quantum mechanics."
> — Richard Feynman, *The Character of Physical Law* (1965)

And sometimes we have nested or longer explanations:

> The Schrödinger equation is a linear partial differential equation that governs the wave function of a quantum-mechanical system.
>
> It is a key result in quantum mechanics, and its discovery was a significant landmark in the development of the subject.

---

## 2. Code Blocks (计算物理刚需)

Here is a typical Python script used for plotting a wave function in 1D infinite potential well:

```python
import numpy as np
import matplotlib.pyplot as plt

def wave_function(n, x, L):
    """Calculate the normalized wave function."""
    return np.sqrt(2/L) * np.sin(n * np.pi * x / L)

# Parameters
L = 1.0
x = np.linspace(0, L, 1000)

plt.plot(x, wave_function(1, x, L), label="n=1")
plt.title("Quantum Well Ground State")
plt.show()
```

And a simple shell command for compiling a C++ simulation:

Bash

```bash
g++ -O3 -fopenmp monte_carlo.cpp -o mc_sim
./mc_sim --particles 100000
```

## 3. Lists and Data (列表与表格)

Physics research often requires structured data:

### Standard Model Fermions (Unordered List)

- Quarks
  - Up, Down
  - Charm, Strange
  - Top, Bottom
- Leptons
  - Electron, Electron Neutrino
  - Muon, Muon Neutrino

### Experimental Steps (Ordered List)

1. Calibrate the interferometer.
2. Isolate the optical table from vibrations.
3. Record the interference fringes.

### Data Table (表格)

| **Particle** | **Symbol** | **Mass (MeV/c²)** | **Charge (e)** |
| ------------ | ---------- | ----------------- | -------------- |
| Electron     | e⁻         | 0.511             | -1             |
| Proton       | p⁺         | 938.27            | +1             |
| Neutron      | n⁰         | 939.57            | 0              |

------

## 4. Mathematical Formulas (公式测试)

If MathJax or KaTeX is enabled, these should render perfectly.

Inline equation: The mass-energy equivalence is described by \\(E = mc^2\\), where \\(c\\) is the speed of light.

Display equation (The Time-Dependent Schrödinger Equation):

$$ i\hbar \frac{\partial}{\partial t} \Psi(\mathbf{r},t) = \left [ \frac{-\hbar^2}{2m}\nabla^2 + V(\mathbf{r},t) \right ] \Psi(\mathbf{r},t) $$

End of test page.