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

I'm the maintainer of <a href="https://cran.r-project.org/web/packages/stylest">stylest</a>, created with <a href="https://github.com/patperry">Patrick O. Perry</a> and <a href="https://github.com/ArthurSpirling/">Arthur Spirling</a>. It's written in R and built on top of <a href="https://cran.r-project.org/web/packages/corpus/index.html">corpus</a>.

* We're on <a href="https://cran.r-project.org/web/packages/stylest">CRAN</a>! Install using `install.packages("stylest")`.

* Read the <a href="https://cran.r-project.org/web/packages/stylest/vignettes/stylest-vignette.html">vignette</a>.

* Read all about it! The paper is forthcoming in _Political Analysis_.

#### leaflet.providers: map provider metadata for `leaflet`

I wrote <a href="https://rstudio.github.io/leaflet.providers/">leaflet.providers</a> while interning at <a href="https://shiny.rstudio.com/">RStudio</a> on the Shiny team.

* Install from CRAN using `install.packages("leaflet.providers")`.

* Check out the <a href="https://rstudio.github.io/leaflet.providers/">documentation</a>.

#### corpus: fast text processing

I'm the maintainer for <a href="https://cran.r-project.org/web/packages/corpus">corpus</a>, written by my colleague <a href="https://github.com/patperry">Patrick O. Perry</a>.

* Install from CRAN using `install.packages("corpus")`.

#### zipR: Pythonic zip(), aka a better cbind() for R

I am the creator and maintainer of <a href="https://cran.r-project.org/web/packages/zipR/">zipR</a>, which implements Python-style zip().

* Install from CRAN using `install.packages("zipR")`.

* View a <a href="https://leslie-huang.github.io/zipr/zipr_demo.html">demo</a>.


<p style="text-align: center;">&bull; &bull; &bull;</p>


# Old stuff

#### Twitter network models (on hiatus since 2017)
I wrote some tools to scrape information about a Twitter user's followers and those followers' followers, in order to model networks between social media users.

* See the Python repo <a href="https://github.com/leslie-huang/twitter-ssscraper">here</a>, and the R repo <a href="https://github.com/leslie-huang/twitter-scrapeR">here</a>.

* I'm developing another <a href="https://github.com/leslie-huang/twitterNetworkGraphR">custom R library for scraping and visualizing n-degree networks</a>.
