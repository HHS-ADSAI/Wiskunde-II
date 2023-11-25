---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
---

# Calculus
Calculus is de wiskunde van het differentieren en integreren. 

## Verandering van een functie

```{code-cell}
import matplotlib.pyplot as plt
import numpy as np

# create 1000 equally spaced points between -10 and 10
x = np.linspace(-10, 10, 1000)

# calculate the y value for each element of the x vector
y = x**2 + 2*x + 2  

fig, ax = plt.subplots()
ax.plot(x, y)
```
