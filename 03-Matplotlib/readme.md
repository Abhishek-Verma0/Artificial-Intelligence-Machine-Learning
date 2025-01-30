# Matplotlib Quick Start Guide

Welcome to the **Matplotlib Quick Start Guide** repository! This guide provides an introduction to Matplotlib, a powerful library for creating static, animated, and interactive visualizations in Python.

## Installation

To install Matplotlib, use:
```bash
pip install matplotlib
```

## Basic Example

```python
import matplotlib.pyplot as plt

x = [1, 2, 3, 4, 5]
y = [10, 20, 25, 30, 50]

plt.plot(x, y, marker='o', linestyle='-')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('Basic Line Plot')
plt.show()
```

## Features Covered
- Line plots
- Bar charts
- Scatter plots
- Histograms
- Customizing plots (colors, labels, legends, etc.)

## Documentation
For detailed documentation, visit the [Matplotlib Official Docs](https://matplotlib.org/stable/contents.html).

## License
This project is licensed under the MIT License.
