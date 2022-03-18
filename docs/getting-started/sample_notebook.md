---
type = "docs"
title = "None"
description = "None"
weight = 900
---

<!--
AUTOGENERATED FROM test\testdata\generic_notebook\sample_notebook.ipynb
PLEASE UPDATE THE JUPYTER NOTEBOOK AND REGENERATE THIS FILE USING scripts/nb_to_md.py.-->

<style>
.notebook-links {display: flex; margin: 1em 0;}
.notebook-links a {padding: .75em; margin-right: .75em; font-weight: bold;}
a.colab-link {
padding-left: 3.25em;
background-image: url(/docs/images/logos/colab.ico);
background-repeat: no-repeat;
background-size: contain;
}
a.github-link {
padding-left: 2.75em;
background-image: url(/docs/images/logos/github.png);
background-repeat: no-repeat;
background-size: auto 75%;
background-position: left center;
}
</style>
<div class="notebook-links">
<a class="colab-link" href="https://colab.research.google.com/github/kubeflow/website/blob/master/test\testdata\generic_notebook\sample_notebook.ipynb">Run in Google Colab</a>
<a class="github-link" href="https://github.com/kubeflow/website/blob/master/test\testdata\generic_notebook\sample_notebook.ipynb">View source on GitHub</a>
</div>

```python
dataset = 'sample_data'
gpu_type = 'A100'
```


```python
import tensorflow
import datetime

print(f"Time: {datetime.datetime.now()}")

a = 10
b = a + 5 #15
```


```python
from IPython.display import Image

url = 'https://raw.githubusercontent.com/SAME-Project/SAME-samples/main/test-artifacts/FaroeIslands.jpeg'

print(f"Time: {datetime.datetime.now()}")

a = a + 5
b = b + 10 #25

from IPython import display
display.Image(url)

```


```python
import plotly

print(f"Time: {datetime.datetime.now()}")

def some_math(x, z) -> tuple:
    return (round(x + z, 2), round(x / z, 2))

a = a * 20
b = b * 100 #2500

print(f"B = {b}")
```


```python
import numpy as np
import matplotlib.pyplot as plt
import scipy.stats as stats

print(f"Time: {datetime.datetime.now()}")

mu = 0
std = 1

x = np.linspace(start=-4, stop=4, num=100)
y = stats.norm.pdf(x, mu, std)

a = a + 5
b = b + 10 # 2515 

plt.plot(x, y)
plt.show()
```


```python
import requests
import pandas as pd
import plotly.figure_factory as ff
import chart_studio.plotly as py

print(f"Time: {datetime.datetime.now()}")

url = 'https://raw.githubusercontent.com/SAME-Project/SAME-samples/main/test-artifacts/test.csv'
df = pd.read_csv(url)

a = a * 1000
b = b / 67 # 37.5373134328

df.describe()
```


```python
a = a + 5
b = b + 10 # 47.5373134328
print(f"Time: {datetime.datetime.now()}")
```


```python
g = some_math(8, 21)
print(f"Time: {datetime.datetime.now()}")
```


```python
j = g[0]
k = g[1]

print(f"Time: {datetime.datetime.now()}")

a = a + 5
b = b + 10 # 57.5373134328

print(f"j: {j}")
```


```python
print(f"k: {k}")

print(f"Time: {datetime.datetime.now()}")

a = a + 5
b = b + 10 # 67.5373134328
```


```python
print("0.0.2")
print(f"Time: {datetime.datetime.now()}")
```


```python
print(f"Accessing the value of B: {b}")
print(f"Time: {datetime.datetime.now()}")
```


```python

```


<div class="notebook-links">
<a class="colab-link" href="https://colab.research.google.com/github/kubeflow/website/blob/master/test\testdata\generic_notebook\sample_notebook.ipynb">Run in Google Colab</a>
<a class="github-link" href="https://github.com/kubeflow/website/blob/master/test\testdata\generic_notebook\sample_notebook.ipynb">View source on GitHub</a>
</div>