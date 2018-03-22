---
layout: page
title: Research
permalink: /research/
---

### Estimating the distribution of state power at the UN using topic models

I use variation in the influence of states on the UN's agenda to estimate the distribution of power. For this project, I scraped original datasets of statements made at the UN and resolutions passed by the UN using Python. I optimized an LDA topic model to extract states' priorities from their speeches and used panel data econometrics to estimate the relationship between states' priorities and resolutions passed by the UN.

* This project was submitted as my Qualifying Paper, a requirement to qualify as a PhD candidate, and earned unanimous "high pass" grades.

* A revised version of this project will be part of my dissertation.

### Sentiment analysis of peace negotiations

Can sentiment analysis predict whether peace talks will fail or succeed? Using the statements published by the FARC guerrilla group and the Colombian government during the peace talks that ultimately ended a half-century-long civil war, I developed a dynamic model that estimates whether each side's willingness to negotiate during the peace talks. I use this model to explain how the peace process responds to violent events.

For this project, I constructed an original Spanish-language corpus of documents scraped from the official websites of the guerrilla group FARC, the president of Colombia, and the peace negotiators using Python. The main analysis was done in R.

* The repos are <a href="https://github.com/leslie-huang/MA-thesis-analysis">here</a> (for the main analyis) and <a href="https://github.com/leslie-huang/MA-thesis-scrapers">here</a> (for the scrapers).

<<<<<<< HEAD:04_projects.md
* View a sentiment analysis demo <a href="https://leslie-huang.github.io/sentiment_demo/sentiment.html">here</a>.

* I wrote a custom R library for this project (current working version is <a href="https://github.com/leslie-huang/faRc-sentiment-analysis-library">here</a>).

* This work was submitted as my MA Paper, as part of my PhD coursework, and earned unanimous "high pass" grades.
=======
* I am refactoring this code into an R package (current version is <a href="https://github.com/leslie-huang/MApkg">here</a>).

* This work was submitted as my MA paper and was awarded unanimous "high pass" grades, <a href="https://leslie-huang.github.io/MA_paper.pdf">here</a>.
>>>>>>> parent of e267b60... updated research projects:04_research.md


### NYC restaurant grades visualizer

I built an interactive command-line tool in Python that provides users with efficient visualizations of health inspection grades from the NYC Department of Health. The user can view a restaurant's grades over time and compare that restaurant with others in the same neighborhood or category. The user can also search for the restaurant with the fewest (or most) health code violations in a given neighborhood or category.

* Check out a demo of the program and its visualization options <a href="https://leslie-huang.github.io/restaurant_demo/Using_the_restaurant_grades_visualizer.html">here</a>.

* See the repo <a href="https://github.com/leslie-huang/restaurant-inspection-grades-visualizer">here</a>.

### Twitter network data scraper

(In progress.) I wrote some scripts to scrape information about a Twitter user's followers and those followers' followers, in order to model networks between social media users.

* See the Python repo <a href="https://github.com/leslie-huang/twitter-ssscraper">here</a>, and the R repo <a href="https://github.com/leslie-huang/twitter-scrapeR">here</a>.

* I'm developing my work in R in a <a href="https://github.com/leslie-huang/twitterNetworkGraphR">custom R library for scraping and visualizing n-degree networks</a>.

### Using Naive Bayes-style techniques to estimate Supreme Court ideology

I scraped Supreme Court opinions from 2003-2015 and constructed a novel dataset using Python. Using the "Wordscores" method, which is similar to a Naive Bayes classification. I estimated ideological positions for opinions, which I aggregated into overall scores for justices. I find a strong correlation between my machine-generated scores and those assigned to the justices by expert coders.

* See the repo <a href="https://github.com/leslie-huang/supreme-court-opinion-wordscores">here</a>.

### Work as a research assistant

* Structural topic models to learn about Antarctica: As a research assistant in the Environmental Studies department, I applied unsupervised machine learning techniques to a dataset of documents pertaining to Antarctica. I cleaned and created the dataset in Python and pre-processed the documents, and optimized the model using the `stm` and `quanteda` packages.

* Network graph simulations: As a research assistant in the Politics department, I wrote and refactored code to simulate network graphs as part of a study to determine the implications of incomplete sampling of networks.
