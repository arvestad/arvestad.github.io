---
title: "alv: an alignment viewer"
excerpt: "View your DNA or protein multiple-sequence alignments right at your command line. No need to launch a GUI!<br/><img src='/images/alv.png'>"
collection: portfolio
---

## Features

* Command-line based, no GUI, so easy to script viewing of many (typically small) MSAs.
* Reads alignments in FASTA, Clustal, PHYLIP, and Stockholm formats.
* Output is formatted to suit your terminal. You can also set the alignment width with option `-w`.
* Can color alignments of coding DNA by codon's translations to amino acids.
* Guesses sequence type (DNA/RNA/AA/coding) by default. You can override with option `-t`.
* Order sequence explicitly, alphabetically, or by sequence similarity.
* Restrict coloring to where you don't have indels or where there is a lot of conservatio
n.

## Where to find it

* Plain installation: you find `alv` on <a href="https://pypi.org/project/alv/">PyPI</a>. Run `pip install alv` and you are done.
* Using Anaconda? <a href="https://anaconda.org/bioconda/alv">`alv` is part of bioconda</a>. Install with `conda install -c bioconda alv`.
* Source code: see the <a href="https://github.com/arvestad/alv">github repository</a>.

<img src='/images/alv_pf00005.png'>

## Please cite

Arvestad, (2018). alv: a console-based viewer for molecular sequence alignments. Journal of Open Source Software, 3(31), 955, https://doi.org/10.21105/joss.00955

```
@Article{alv2018,
  author = 	 {Lars Arvestad},
  title = 	 {alv: a console-based viewer for molecular sequence alignments},
  journal = 	 {Journal of Open Source Software},
  year = 	 2018,
  volume = 	 3,
  number = 	 31,
  pages = 	 955,
  doi =          {https://doi.org/10.21105/joss.00955}
}
```
