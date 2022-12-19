# Comparing Theories of One-Shot Play Out of Treatment
Everything code related to the paper ["Comparing Theories of One-Shot Play Out of Treatment" with Christoph Kuzmics](https://doi.org/10.1016/j.jet.2022.105554)

## z-Tree code
The code for the first part (two-action games) was written for z-Tree v3.5 and for the second part (three-action games), it was updated and (partly) re-written for z-Tree version 3.6.7 (fontsize 18).

## Instructions
[Instructions: two-action games](instructions/instructions_2_actions.pdf) - In the other version of the instructions only the order of hawk-dove games and matching-pennies was swapped. 

[Instructions: three-action games](instructions/instructions_3_actions.pdf) - In the other version of the instructions only the order of hawk-middle-dove games and rock-paper-scissors games was swapped. 


## R-code
### Generating the predictions for each theory
-missing-

### Out-of-treatment testing
To make out-of-treatment testing easier, we have created the [R package oottest](https://github.com/PhilippKuelpmann/oottest) ([CRAN link](hhttps://CRAN.R-project.org/package=oottest)).
Part of it is the vignette [reproduce_paper](https://cran.r-project.org/web/packages/oottest/vignettes/reproduce_paper.html), which shows you step by step how to reproduce every figure and graph from the paper.


## Data
### Choice data
The choice data is available as part of the aforementioned [out-of-treatment testing package](https://CRAN.R-project.org/package=oottest), the data description can be found in R or the [reference manual](https://cran.r-project.org/web/packages/oottest/oottest.pdf).


#### Subject-level choice data
In the folder 'subject-level-choice-data', you can find the choice data for all games.
A subject is identified by a subject number within a file, i.e., subject 2 in two_action_games.csv is not the same subject as subject 2 in three_action_games.csv.


### Choice data, risk-aversion, level-k reasoning and more subject level data
We have not used the risk-aversion, level-k reasoning and other subject level data (as gender, age, ...) in the paper.
I have chosen to not make it public, as it includes detailed data about individual subjects. Furthermore, the data is not prepared/commented sufficiently to be useful without an explanation.
Thus, if you are interested in the entire data, please send me an email. I'll gladly share the data and help making sense of it.
