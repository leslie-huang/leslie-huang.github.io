---
layout: page
title: Software
permalink: /software/
---

# Python

#### How Many Word Senses?

I wrote a library (using the term loosely) to implement my unsupervised method to identify the number of word senses using contextualized representations.

This workflow includes, from start to finish: SQL databases queried through Python. Flexible options for selecting contexts containing a target word and extracting the contextualized representations from <a href="https://github.com/google-research/bert">BERT</a> / <a href="https://allennlp.org/elmo">ELMo</a> / (non-contextualized) <a href="http://fasttext.cc">fastText</a>. Dimensionality reduction and cross-validated clustering using <a href="https://scikit-learn.org">sklearn</a> and other goodies. Evaluation against ground truth data (WordNet). Batch scripting to run a gridsearch pipeline for 1000s of words. Plus tools for visualizing manually annotated data (see the <a href="https://medium.com/@leslie_huang/automatic-extraction-of-word-senses-from-deep-contextualized-word-embeddings-2f09f16e820">Medium</a> post for some fun graphs).

* Code, including demo Jupyter Notebooks, is up on <a href="https://github.com/leslie-huang/howmanywordsenses">GitHub</a>.

* Read the write-up "Can we identify word senses from deep contextualized word embeddings without supervision?" on <a href="https://medium.com/@leslie_huang/automatic-extraction-of-word-senses-from-deep-contextualized-word-embeddings-2f09f16e820">Medium</a>.



<p style="text-align: center;">&bull; &bull; &bull;</p>

# R packages

#### stylest: Estimating speaker style distinctiveness in R

I'm the maintainer of <a href="https://cran.r-project.org/web/packages/stylest">stylest</a>, created with <a href="https://github.com/patperry">Patrick O. Perry</a> and <a href="https://github.com/ArthurSpirling/">Arthur Spirling</a>.

* We're on <a href="https://cran.r-project.org/web/packages/stylest">CRAN</a>! Install using `install.packages("stylest")`.

* Read the <a href="https://cran.r-project.org/web/packages/stylest/vignettes/stylest-vignette.html">vignette</a> and check out the <a href="https://doi.org/10.1017/pan.2019.49">paper</a>.

#### leaflet.providers: map provider metadata for `leaflet`

I wrote <a href="https://rstudio.github.io/leaflet.providers/">leaflet.providers</a> while interning at <a href="https://shiny.rstudio.com/">RStudio</a> on the Shiny team.

* Install from CRAN using `install.packages("leaflet.providers")`.

#### corpus: fast text processing

I'm the maintainer for <a href="https://cran.r-project.org/web/packages/corpus">corpus</a>, written by my colleague <a href="https://github.com/patperry">Patrick O. Perry</a>.

* Install from CRAN using `install.packages("corpus")`.

#### zipR: Pythonic zip(), aka a better cbind() for R

I am the creator and maintainer of <a href="https://cran.r-project.org/web/packages/zipR/">zipR</a>, which implements Python-style zip().

* Install from CRAN using `install.packages("zipR")`.
