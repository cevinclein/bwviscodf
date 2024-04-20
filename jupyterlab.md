**Table of Contents**

[TOC]

# Introduction to JupyterLab
---

Jupyter and offers a flexible and powerful toolkit for working with projects involving Jupyter notebooks, code, and data. This guide will cover all the essentials to get you started with JupyterLab, including detailed steps and examples.

## What is JupyterLab?
---

JupyterLab is an integrated development environment (IDE) that provides a flexible and scalable interface for the Jupyter Notebook system. It supports interactive data science and scientific computing across over 40 programming languages (including Python, Julia, and R).

**Key features:**

- Code, compile, and run in multiple languages.
- A modular interface with customizable layout.
- Integration with Git and other version control systems.
- Supports real-time collaboration.

# Starting JupyterLab
---

On the bwVisu nav-bar click `Interactive Apps` --> `JupyterLab`.
Than specify the resources and click `Launch`. This will open JupyterLab in your current web browser.

## The JupyterLab Interface
---

**Left Sidebar:**
:    Contains file browser, running kernels, command palette, and extensions.

**Main Workspace:**
:    Area where notebooks and files are displayed.

**Top Menu:**
:     Provides access to file, edit, view, and run commands.

# Working with Notebooks
---

You can create a new notebook via the `+` button in the file browser or the `File` menu. Enter your code in a cell, and press ++shift+enter++ to execute the code in that cell. Every cell accepts valid code and module imports. Example Python code:

```{.python linenums="1" title="Python"}
from matplotlib import pyplot as plt
import numpy as np

# Generate 100 random data points along 3 dimensions
x, y, scale = np.random.randn(3, 100)
fig, ax = plt.subplots()

# Map each onto a scatterplot we'll create with Matplotlib
ax.scatter(x=x, y=y, c=scale, s=np.abs(scale)*500)
ax.set(title="Some random data, created with JupyterLab!")
plt.show()
```

Markdown cells allow you to add formatted text to explain your code, using Markdown syntax.

**Advanced Features:**

- JupyterLab supports numerous extensions that enhance functionality, such as the JupyterLab Git extension.
- Interactive IPython widgets can enhance notebook interactivity.

# Tips and Tricks
---

comese





