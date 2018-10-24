# Bayesian Inference and the Blue Wave

This project used Bayesian inference to predict the vote share Democratic candidates will receive in the 2018 midterm Senate elections. These midterm elections are of particular interest to Democrats, as they present an opportunity for a "Blue Wave" in the Senate in which Democrats can regain the majority. However, to achieve this, they must keep all of the seats previously held by Democrats and gain 2 additional seats. Previous senate election data served as the prior, recent polling data served as the likelihood, and Markov chain Monte Carlo simulations created the posterior distribution. An estimated 26 seats will go to Democrats in this election, resulting in a 49% minority which means a Senate Blue Wave is unlikely. On an optimistic note, forecasts are favorable for a Blue Wave in the House of Representatives.  

## Repository Contents
1. Jupyter Notebook
2. Presentation
3. Assets

## Notes
- There were no polls available on Hawaii and Wyoming's candidates.
- California has a "top two" primary election system where the two candidates with the highest amount of votes in the primary election advance to the general election, regardless of party affiliation. Thus, there are two Democratic candidates. For the purposes of this project, Dianne Feinstein (incumbent) is being treated as the Democratic candidate and her opponent, Kevin de Leon, is being treated as the other candidate.

## Data Sources
- Prior election data comes from the FEC's 2014 and 2016 Official Senate Election Results
- Polling data comes from FiveThirtyEight
