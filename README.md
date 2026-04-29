# Data processing Python notebooks

Jupyter notebooks for visualizing STM (Scanning Tunneling Microscopy) data and molecular dynamics radial distribution functions on ZrTe$_5$ / Au, supporting the paper on ultrastrong Au–Te bonding.

Data published on Zenodo: https://zenodo.org/records/19680005

Package versions used are explicitly printed in the notebooks for better reproducibility.

### Installation

Install required packages quickly by:

```
pip install -r requirements.txt
```

### Usage

The notebooks automatically download required data files from Zenodo into a local `data/` directory if they're missing, and reuse the cache on subsequent runs. Simply run all cells.

HTML exports of all notebooks are also supplied in the repository. To just view the HTML files locally, download them (green "Code" button, "Download ZIP").

### Notebooks

- `fig1.ipynb` — STM topography images at 9 K and 300 K
- `fig2.ipynb` — STM topography and FFT images
- `fig3.ipynb` — Radial distribution functions (RDF) of freestanding and gold-supported ZrTe$_5$ mono- and bilayers, computed with OVITO

### About

Jupyter notebooks for visualising the data found at: https://zenodo.org/records/19680005
