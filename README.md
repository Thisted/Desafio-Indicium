# Desafio-Indicium

## Requirements
- Ubuntu / macOS / Windows
- Python3

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install matplotlib
pip install pandas
pip install numpy
```

## Usage

Run `Desafio_Indicium` or `Desafio_Indicium_Notebook` for usage. 

The outputs are saved as [PNG](https://pt.wikipedia.org/wiki/PNG) and [CSV](https://pt.wikipedia.org/wiki/Comma-separated_values) files.

```python
import matplotlib.pyplot as plt
import pandas as pd
import numpy as np

pd.read_csv('filepath.csv') # returns DataFrame
DataFrame.merge(df, columns) # returns two DataFrames merged together
DataFrame.groupby(columns) # returns a grouped object with information about the groups
plt.plt(data) # return the plotted data
plt.show() # returns the image of the plotted data
