---
jupytext:
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.17.3
kernelspec:
  display_name: base
  language: python
  name: python3
---
# Coding that executes right away

Here we'll show a plot, called: "Sine wave":
```{code-cell} ipython3
:tags: ["auto-execute-page"]

import matplotlib.pyplot as plt
import numpy as np

x = np.linspace(0, 10, 100)
y = np.sin(x)

plt.plot(x, y)
plt.title("Sine wave")
plt.show()
```
