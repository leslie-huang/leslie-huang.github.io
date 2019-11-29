---
layout: page
title: Papers
permalink: /papers/
---


# Dissertation

#### "Contexualized NLP tools for unsupervised text analysis" (working title)

* Committee: <a href="https://www.nyu.edu/projects/spirling/">Arthur Spirling (chair)</a>, <a href="http://www.kyunghyuncho.me/">Kyunghyun Cho</a>, <a href="http://as.nyu.edu/content/nyu-as/as/faculty/jonathan-nagler.html">Jonathan Nagler</a>


# Papers

#### Huang, L., P. Perry, and A. Spirling. "A General Model of Author 'Style' with Application to the UK House of Commons, 1935–2018"

We consider the merits of claims that Members of Parliament (MPs) in the UK have become more ‘boring’ over time—that is, less distinctive from one another in terms of their speech and style. We review theory and previous findings in the area, and note their ambiguity in predictions on this matter. We then provide an efficient new measurement model of distinctiveness that extends traditional efforts to statistically characterize the ‘style’ of authors, and apply it to a corpus of Hansard speeches from 1935 to 2018. In the aggregate, we find no evidence for the claim of increased boringness. But this hides intriguing covariate effects: at the MP level, panel regression results demonstrate that on average, more senior backbenchers tend to be less interesting in speech terms. We also show, however, that this pattern is changing: in recent times, it is more experienced MPs who speak most distinctively.

* Accepted (watch this space!).

#### Huang, L. "Estimating the distribution of state power at the UN using topic models."

What accounts for variation in states' influence on the agenda at the UN General Assembly (GA), and how can we use this variation to understand the underlying distribution of power in international relations? To answer these questions, I introduce a dataset of statements given at the UN's annual General Debate, and a corresponding dataset of GA resolutions. Using unsupervised machine learning, I extract each state's issue priorities from their statements and assess the extent to which resolutions passed by the GA address these priorities. Contrary to my expectations, I do not find convincing support for the hypotheses that Security Council members or wealthier countries shape the UN's agenda to fit their interests. I suggest this result is due to countervailing efforts to block and advance resolutions.

* This project was submitted as my Qualifying Paper, a requirement to qualify as a PhD candidate in political science, and earned unanimous “high pass” grades.


# Old stuff


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
