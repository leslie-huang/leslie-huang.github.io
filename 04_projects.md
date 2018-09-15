---
layout: page
title: Projects
permalink: /projects/
---

### Dissertation

Coming soon...

### Named Entity Recognition system for political speech

I implemented an NLP pipeline for NER for political speeches at the UN. This included Part-of-Speech tagging, chunking, and an ensemble of classifiers for NE (MaxEnt MM, multiclass Naive Bayes, and Decision Trees), utilizing the tools available in NLTK and sk-learn, plus some old-fashioned elbow grease: I manually tagged 140,000+ tokens for the training/test data!

* See the repo <a href="https://github.com/leslie-huang/UN-named-entity-recognition"> here</a>.

### Estimating the distribution of state power at the UN using topic models

What accounts for variation in states' influence on the agenda at the UN General Assembly (GA), and how can we use this variation to understand the underlying distribution of power in international relations? To answer these questions, I introduce a dataset of statements given at the UN's annual General Debate and a dataset of GA resolutions. Using unsupervised machine learning techniques, I extract each state's issue priorities from their statements and assess the extent to which resolutions passed by the GA address these priorities. Contrary to my expectations, I do not find convincing support for the hypotheses that Security Council members and wealthier countries have greater influence on the GA's agenda. I suggest these results are due to countervailing efforts to get a resolution on an agenda and to block it from the agenda.

* This project was submitted as my Qualifying Paper, a requirement to qualify as a PhD candidate in political science, and earned unanimous “high pass” grades.

* A revised version of this project will be part of my dissertation.

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
