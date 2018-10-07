# Multilevel modeling: frequentist and Bayesian approaches

This repository contains the RMarkdown script to generate slides for an introductory course on Bayesian multilevel modeling (created with ioslides, .html output).

_Summary_
Multilevel models are ideally suited to the analysis of data that have a hierarchical structure, such as it is the case in psychology and neuroscience, where observations (e.g. trials of an experiment) are grouped according to 'observational clusters' (e.g., the participants of the experiment). In this tutorial I will first introduce multilevel models (also known as hierarchical or mixed-effects) in a frequentist setting, using R ([www.r-project.org/](https://www.r-project.org/)) and the lme4 library. Next, I will move toward a Bayesian approach, and illustrate how to fit multilevel models in a Bayesian framework, using Stan ([mc-stan.org/](http://mc-stan.org/)) and its R interface (see here for installation instructions: [github.com/stan-dev/rstan/wiki/RStan-Getting-Started](https://github.com/stan-dev/rstan/wiki/RStan-Getting-Started)). One of the advantages of Stan is that it enables users to build the model they want, instead of having to choose from a limited set of default models. Time permitting, we will see through a series of worked examples how this can be particularly useful in experimental psychology, as it allows estimating at the group level more realistic models of decision making processes (e.g. mixture or drift-diffusion models).

