---
layout: page
title: Projects
permalink: /projects/
---

Working papers can be found <a href="https://leslie-huang.github.io/papers/">over here</a>; everything else is collected on this page.

### Dissertation: "Evaluating the state of democracy using natural language processing"

* More information soon.

### Named Entity Recognition system for political speech

I implemented an NLP pipeline for NER for political speeches at the UN. This included Part-of-Speech tagging, chunking, and an ensemble of classifiers for NE (MaxEnt MM, multiclass Naive Bayes, and Decision Trees), utilizing tools from NLTK and sklearn, plus some old-fashioned elbow grease: I manually tagged 140,000+ tokens for the training/test data!

* See the repo <a href="https://github.com/leslie-huang/UN-named-entity-recognition"> here</a>.

### Diffusion of information about political preferences in social networks

Social media may facilitate the formation of echo chambers of polarized speech; but it provides valuable insight into mapping the connections between preferences on different issues---for example, the relationship between one's positions on income taxes or marriage equality---and how these connections influence the spread of political information---in this case, through retweets. Using 9.5 billion tweets from 2017 Women's March (kindly provided by the NYU SMAPP lab), I find that political preferences bound to core liberal issues---reproductive rights, gender equality, marriage equality, and climate change---are tightly correlated and that linking multiple issues together increases the engagement that a social media posting receives.

### Sentiment analysis of FARC-Colombia negotiations

Can sentiment analysis predict whether peace talks will fail or succeed? Using the statements published by the FARC and the Colombian government, I developed a dynamic model that estimates whether each side's willingness to negotiate during the peace talks. I use this model to explain how the peace process responds to violent events.

For this project, I constructed an original Spanish-language corpus of documents scraped from the official websites of the guerrilla group FARC, the president of Colombia, and the peace negotiators using Python. The main analysis was done in R.

* View a sentiment analysis demo <a href="https://leslie-huang.github.io/sentiment_demo/sentiment.html">here</a>.

* I wrote a custom R library for this project (messy, working version is <a href="https://github.com/leslie-huang/faRc-sentiment-analysis-library">here</a>).

* This work was submitted as my MA Thesis, as part of my PhD coursework, and was awarded unanimous "high pass" grades.

### Naive Bayes-style estimation of Supreme Court ideology

I scraped Supreme Court opinions from 2003-2015 and constructed a novel dataset using Python. Using the "Wordscores" method (similar to a Naive Bayes classifier). I estimated ideological positions for opinions, which I aggregated into overall scores for justices. I find a strong correlation between my machine-generated scores and those assigned to the justices by expert coders.

* See the repo <a href="https://github.com/leslie-huang/supreme-court-opinion-wordscores">here</a>.

### Work as a research assistant

* Structural topic models to learn about Antarctica: As a research assistant in the Environmental Studies department, I applied unsupervised machine learning techniques to a dataset of documents pertaining to Antarctica. I cleaned and created the dataset in Python and pre-processed the documents, and optimized the model using `stm` and `quanteda`.

* Network graph simulations: As a research assistant in the Politics department, I wrote and refactored code to simulate network graphs as part of a study to determine the implications of incomplete sampling of networks.
